---
title: "How much should Obsidian plugins be regulated?"
description: "Clear rules and guidelines for community plugins should exist, but to what extent?"
date: 2026-10-11
author: Duskfall
---
I don't know. There's likely neither even a conclusive answer everyone would agree on nor one that would suffice for all situations.

## Standards are helpful for shared or common functions

I was updating some of the community plugins I have installed and noticed that some (QuickAdd and Notebook Navigator) will automatically create a popup showing the latest release notes for the plugin.

As far as I can tell, those release notes aren't done in some standard way. QuickAdd appears to fetch the latest release notes from its repo while Notebook Navigator embeds its release notes in directly (or somehow fetches much faster than QuickAdd).

Displaying plugin release notes to the end user in the app is something plugin developers desire. Sure, people can discover changes by getting notified of releases on GitHub or posts in the Obsidian Discord,[^1] but developers want something that requires never leaving the app to see.

It's an example of something I could possibly see Obsidian's developers making some standard or API for. Developers want it, and to be honest, it is quite convenient as a user. I hate having to go open up my browser to go see what's actually in the update.

## Obsidian has standardized things for community plugins before

Obsidian has definitely standardized elements of the community plugin system before. One of the more recent examples I can think of was the cool new settings API they introduced in Obsidian 1.13.0, which makes things much more consistent between core and community plugin settings.

I was not a plugin author pre-1.13.0, but to my understanding (and from what I saw in community plugin settings during this time), plugin authors had to essentially create their own UI for their plugin settings from scratch. After 1.13.0, I saw that plugin settings felt more consistent across plugins and could now be searched through with Obsidian's new settings search.

Actually, it feels like the team has thought a lot about community plugins as of late. 1.13.0 saw the new settings API, and just before that we got the big new [Community Directory update](https://obsidian.md/blog/future-of-plugins/) that led to the massive uptick in Obsidian plugins being released.

Hm, you know, maybe they're standardizing things more so that AI-coded plugins are less... well, terrible? Had the original settings system remained, I imagine we'd see all sorts of wacky settings interfaces that connected terribly with one another. Making a plugin is easier than ever, but that also makes turning Obsidian into a mishmash of conflicting styles and practices sounds like hell.[^2]

## Plugin development in the LLM era

I hadn't originally intended for this post to be about LLMs, but it seems relevant to whatever people could get out of this. People are going to vibecode or otherwise use LLMs while developing their plugins,[^3] you cannot realistically ban AI-made or AI-assisted plugins at this point.

While Obsidian's developers haven't done too much to integrate LLMs as a consumer-facing feature of the app, I think they do recognize that software engineering is veering in the direction of LLMs.

So they've started subtly making it easier for LLMs to develop plugins in ways that don't completely break the app or interfere with other plugins (an objectively good thing), e.g., creating an AGENTS.md in their sample plugin repository.

The purpose of an AGENTS.md isn't subtle to the average developer. It's obviously something that benefits AI agents. But now the Community Directory, new Settings API, and secrets storage exist. The Community Directory attaches a scorecard to plugins, which rates quality based on a set of Obsidian-specific ESLint rules. This incentivizes developers to make plugins that follow better standards. The new Settings API and secrets storage are clearly intended to give developers a more standard way to approach this common functionality—avoiding a lot of potential issues around LLM-generated interfaces and plugin settings and secrets storage.

They have their benefits for regular developers and users too, but I wonder if these recent changes are being spurred on by the sudden hype and growth around AI. I guess I can't really say what direction Obsidian would have gone in without this AI craze; Steph Ango has only been CEO since 2023 (after AI started getting popular), and Obsidian was in its early stages from 2020–2022 (1.0.0 launched that year).

## It hasn't always worked out perfectly

I like to think standardization is nice and peachy, but it does have costs. The new Community Directory drew the criticism of Obsidian's largest plugin author, zsviczian (who created the Excalidraw plugin), because the scorecard would impact his plugin's credibility because his codebase was old and would need to be majorly refactored to fit Obsidian's new standards.

Plugin authors also need to spend the time migrating their plugins to newer systems like the 1.13.0 Settings API or 1.11.0 Keychain (for storing secrets). Some plugins are abandoned, and will simply never update their plugins to do this.

Maybe that's just the way things go with software, even for plugin systems. Okay, so we clearly cannot force plugins to fit some style. It would limit the flexibility and customization the app prides itself on. Regulation and standardization of how plugins operate is necessary, but I don't really know to what degree that is.

I wish the Obsidian team luck, because it sounds like a really hard balance to strike. I never even got into some of the finer issues with cross-plugin integration, including how sometimes the app is designed around core plugin functions (like navigation through breadcrumbs, tags, and other elements to the built-in File Explorer over community-made file explorers).

[^1]: Which either requires a GitHub account—which non-technical users would likely not care for—or sifting through the many other irrelevant new plugin announcements or plugin updates.
[^2]: And it already felt like too many plugins were doing something that felt un-"Obsidian-like" to begin with. It's hard to maintain consistency when enough people are all working independently and not really adhering to a single style or focus.
[^3]: I'm generally weary of LLMs, but I have to unfortunately admit that even I have asked a chatbot for help with some parts of plugin development. In my defense, it is a completely private plugin and I refuse to publish it until I know what's going on. Even still, it only continued to break as I relied more on the AI... time to start over from scratch /hj.