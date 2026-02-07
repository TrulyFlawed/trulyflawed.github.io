---
title: Ladybird passing 90% of web platform tests is a huge milestone
date: 2026-02-06
author: Duskfall
---
[Andreas Kling][kling], the creator of the [Ladybird web browser][ladybird], has recently announced that the browser began to pass over 90% of [web platform tests][wpt].[^ladybird-wpt-announcement][^ladybird-october-2025-newsletter] This is a major milestone to reach because Apple has restrictions on the use of non-[WebKit][wp-webkit] browser engines on [iOS][wp-ios] and [iPadOS][wp-ipados], which prevents any [browser engine][wp-browser-engine] that doesn't pass 90% of tests to be used on the aforementioned platforms.[^apple-requirements][^ladybird-october-2025-newsletter]

Ladybird is unlikely to release any time soon, with the [alpha release][wp-alpha] still planned for 2026, and a stable version likely years after that.[^ladybird] And so far, a port of Ladybird's browser engine to [mobile operating systems][wp-mobile-os] like [Android][wp-android], iOS, and iPadOS hasn't started in any significant capacity.[^ladybird]

Despite the challenges ahead of Ladybird, this milestone will make porting the browser engine to [Apple's ecosystem][wp-apple-ecosysem] significantly easier, as, they no longer need to worry as much about Apple's alternative browser requirements, which Kling as called "arbitrary."[^ladybird-wpt-announcement]

<!-- External links -->
[kling]: https://twitter.com/awesomekling
[ladybird]: https://ladybird.org
[wpt]: https://web-platform-tests.org/

[wp-webkit]: https://en.wikipedia.org/wiki/WebKit
[wp-ios]: https://en.wikipedia.org/wiki/IOS
[wp-ipados]: https://en.wikipedia.org/wiki/IPadOS
[wp-browser-engine]: https://en.wikipedia.org/wiki/Browser_engine
[wp-alpha]: https://en.wikipedia.org/wiki/Software_release_life_cycle#Alpha
[wp-mobile-os]: https://en.wikipedia.org/wiki/Mobile_operating_system
[wp-android]: https://en.wikipedia.org/wiki/Android_(operating_system)
[wp-apple-ecosysem]: https://en.wikipedia.org/wiki/Apple_ecosystem

<!-- Internal links -->

## References

[^ladybird-wpt-announcement]: {% include citation.html key="ladybird-90-percent-web-platform-tests-announcement-tweet" %}

[^ladybird-october-2025-newsletter]: {% include citation.html key="ladybird-october-2025-newsletter" %}

[^apple-requirements]: {% include citation.html key="apple-alternative-browser-requirements" %}

[^ladybird]: {% include citation.html key="ladybird-site" %}