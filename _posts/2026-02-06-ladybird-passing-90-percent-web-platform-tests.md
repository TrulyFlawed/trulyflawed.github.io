---
title: Ladybird passes Apple's 90% threshold on web-platform-tests
date: 2026-02-13
author: Duskfall
---
On October 5, 2025, the creator of the [Ladybird web browser][ladybird], [Andreas Kling][kling], announced on Twitter (and later, in the Ladybird October 2025 newsletter) that Ladybird had begun to pass over 90% of [web-platform-tests][wpt] (WPT).[^ladybird-wpt-announcement][^ladybird-october-2025-newsletter]

## Porting Ladybird to iOS

Kling has pointed out that passing over 90% of WPT is a major requirement imposed by Apple for allowing developers to make and use a non-[Webkit][w-webkit] [browser engine][w-browser-engine] on iOS.[^ladybird-october-2025-newsletter][^ladybird-wpt-announcement] However there are still many other restrictions Apple has placed that Ladybird is yet to overcome if they want to use their own engine on iOS.[^apple-requirements]

[Open Web Advocacy][w-open-web-advocacy] argued earlier in July 2025 that despite the European Union mandating that Apple allow third-party browser engines on iOS, Apple's restrictions are arguably too burdensome for even Mozilla or Google to consider porting their engines to the operating system—let alone an upcoming player like Ladybird.[^owa-apple-alt-browser-reqs]

It's uncertain if these restrictions will be softened by the time Ladybird begins development of its browser for mobile operating systems, which has not begun in any significant capacity during its pre-alpha stage of development.[^ladybird]

## WPT as a metric for progress

According to Ladybird's October 2025 blog post, a large part of this achievement actually came from an update to the test suite itself, which updated [Wasm][w-wasm] core tests to Wasm 3.0.[^ladybird-october-2025-newsletter] That month, they passed 111,431 new subtests, compared to just 13,405 and 7,497 for the month before and after respectively.[^ladybird-september-2025-newsletter][^ladybird-november-2025-newsletter]

A user on Hacker News who claimed to be "quite heavily involved" with web-platform-tests has said that using it as a metric for progress is not recommended, as its intended more as an engineering resource rather than a user-facing metric of how good a browser is.[^hacker-news-ladybird-wpt]

Despite their efforts, Ladybird is still in pre-alpha, with an alpha release on Linux and MacOS planned for Summer 2026.[^ladybird] That said, it is still a major milestone passed, and despite the work ahead of them, it does represent how far Ladybird has come.

---

## References

[^ladybird-wpt-announcement]: {% include citation.html key="ladybird-90-percent-web-platform-tests-announcement-tweet" %}

[^ladybird-october-2025-newsletter]: {% include citation.html key="ladybird-october-2025-newsletter" %}

[^ladybird-september-2025-newsletter]: {% include citation.html key="ladybird-september-2025-newsletter" %}

[^ladybird-november-2025-newsletter]: {% include citation.html key="ladybird-november-2025-newsletter" %}

[^ladybird]: {% include citation.html key="ladybird-site" %}

[^apple-requirements]: {% include citation.html key="apple-alternative-browser-requirements" %}

[^owa-apple-alt-browser-reqs]: {% include citation.html key="open-web-advocacy-apple-alt-browser-engine-ban-despite-dma" %}

[^hacker-news-ladybird-wpt]: {% include citation.html key="hacker-news-ladybird-passes-90-percent-wpt" %}

<!-- External links
======================== -->
[kling]: https://twitter.com/awesomekling
[ladybird]: https://ladybird.org
[wpt]: https://web-platform-tests.org/

<!-- Wikipedia links -->
[w-webkit]: https://en.wikipedia.org/wiki/WebKit
[w-browser-engine]: https://en.wikipedia.org/wiki/Browser_engine
[w-open-web-advocacy]: https://en.wikipedia.org/wiki/Open_Web_Advocacy
[w-wasm]: https://en.wikipedia.org/wiki/WebAssembly