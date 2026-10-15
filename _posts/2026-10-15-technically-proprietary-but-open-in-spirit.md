---
title: "Technically proprietary, but open in spirit"
description: "Obsidian feels so much more open than most proprietary software"
date: 2026-10-15
author: Duskfall
---
Who's ready for some pro-Obsidian propaganda? Joking, kind of. I'll be upfront, I'm a paying subscriber and plugin developer[^1] for Obsidian, and if you are a die-hard open-source lover who refuses to use proprietary apps altogether, I won't stop you; Obsidian is not for you. Now let's talk about how Obsidian feels so open (to me) despite being proprietary software.

## Most privacy-friendly, user-respecting software is open-source. Most.

As I've tried to move away from Big Tech toward more privacy-friendly software, I've noticed that most of the software here is open-source. Not all of it, but most. It makes sense, a lot of open-source projects aren't run by massive corporations looking to sell your data. Usually they're very upfront about their costs because they don't want to lock you in.

I'm generalizing here a lot, but my point is that open-source tends to have different incentives to proprietary software that leads them to value their community and users more than profits and investors.

Open-source is lovely, and I prefer it where I can, but sometimes I feel a proprietary option can excel while still respecting me as a user. In my case, that app was Obsidian.

## Obsidian is open in other ways

Obsidian is primarily a Markdown editor—Markdown being an open format that is widely used as a simpler way to type up basic HTML. The app also stores notes locally on your file system, so it's all just there on your computer.

At any point, you can:

- Switch to another Markdown editor or import your notes into another app
- Use a tool like Syncthing or some other cloud service to sync your notes across devices
- Publish your notes using third-party services or setting up your own system for that
- Back up all of your notes using a version control system like Git

Cross-device sync and publishing are especially interesting because these are the very services that Obsidian offers as paid add-on subscription services, but which can be done freely or with third-party alternative solutions.

Those services is the primary way Obsidian makes money, and they hardly try to lock you in.

Obsidian's community plugins and themes are another way it feels similar to open-source software. We can tinker with the app all we like too, as the app does not really restrict how plugins and themes can change things.[^2]

Your notes aren't locked away in a cloud server within a proprietary format and you can modify the app to your liking.

## It's obviously still closed-source

Unfortunately it is still closed-source. You can't open a pull request or scour through the app's (deobfuscated) source code, meaning community contributions on the technical side aren't really there. But despite this, I think Obsidian has done a really good job at developing a polished app.

In my experience, rough edges most often come from plugins and how they interact with the core app and one another rather than issues with core Obsidian. The app could go further to be more beginner-friendly, or to have a less immediately cluttered interface, but it does a good job overall compared to other open-source note-taking apps I've tried.

I've found myself really happy with the direction Obsidian has taken recently, especially with Bases and the new Community Directory. Bases gives Obsidian something akin to Notion databases (but in a way that's more intuitive and useful in my opinion[^3]) and the Community Directory addresses many issues the team faced with the mounting community plugin backlog as a consequence of LLM-driven development.

There have been discussions of open-sourcing Obsidian, especially if the company were to go belly-up, but I don't think any plans to open-source the app have been confirmed. It'd probably add a lot of administrative and community management overhead anyway.[^5]

If you were worried about trying Obsidian because it's proprietary, you should still consider trying it. It might not fit for other reasons, but the data is open and a lot of apps support importing Markdown, so if you switch it will be pretty easy to move your data.[^4]

[^1]: It's not published yet, but the fact I've even taken the effort to try developing one should tell you enough about how much I love this app.
[^2]: Though if your plugin is following best practices, it won't try to interfere with core behaviors, undocumented APIs, or things other plugins may rely on. It's important for published plugins, but you can make a private plugin that does whatever you please.
[^3]: Notion's databases feel more like glorified folders than anything else, since pages cannot exist under multiple databases. Obsidian Bases are more interesting to me because they essentially act as filtered views of your notes based on properties and other metadata—allowing notes to exist "under" several bases simultaneously.
[^4]: Unless you're like me and you've laced some of your notes with various plugin-specific or Markdown extension syntax that may not be supported by other apps.
[^5]: Plus perhaps a new wave of idea guys and bickering over what deserves to be a core plugin. Maybe I take the Obsidian team's vision for granted.