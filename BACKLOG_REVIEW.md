# Backlog review: 2026-09-21

Scope: all 47 open pull requests and all 9 open issues in 738/awesome-url-shortener. All proposed PR changes were confined to README.md. Bodies, diffs, and available discussion/review comments were inspected.

This document records proposed dispositions. The original PRs and issues remain open until the maintainer authorizes and applies the plan. The accompanying README incorporates 39 PRs, recommends closing one parked-domain proposal, and leaves seven PRs pending evidence. Eight issues can be resolved; one needs a working service URL.

## Verification and limits

- Checked official homepages, documentation, repository source/license declarations, redirect destinations, and HTTP/TLS responses. Access failures were retried.
- This is a directory review, not an end-to-end audit of every service. No paid accounts, registrations, or production short links were created.
- JavaScript-only pages were inspected through available HTML and public bundles. Browser execution could not be completed because the installed browse runtime lacked its expected Chromium build.
- HTTP 403, DNS failure, and TLS errors are observations, not proof of permanent shutdown. Existing affected services have a separate access-problems category; new inaccessible services are held.
- No GitHub Actions workflows or PR status checks were configured. README structure, ordering, duplicates, links, and whitespace were checked locally.

## Pull requests

| PR | Proposed action | Reason and evidence |
| --- | --- | --- |
| [#31](https://github.com/738/awesome-url-shortener/pull/31) | Incorporate / supersede | Include url1.io. Replace the former Kutt domain with kutt.to based on the upstream warning; resolve the stale PR conflict through this update. [Source](https://github.com/thedevs-network/kutt#readme). |
| [#51](https://github.com/738/awesome-url-shortener/pull/51) | Incorporate / supersede | Include Slug with a short description; repository has GPL-3.0 licensing. [Source](https://github.com/pheralb/slug). |
| [#53](https://github.com/738/awesome-url-shortener/pull/53) | Incorporate / supersede | Include the hosted service and link directly to its source repository in the self-hosted section. [Source](https://github.com/ramesaliyev/kes.im). |
| [#56](https://github.com/738/awesome-url-shortener/pull/56) | Hold open | short.reus.nc returned HTTP 521 on repeated checks. Verify restoration or provide a working replacement. [Source](https://short.reus.nc). |
| [#58](https://github.com/738/awesome-url-shortener/pull/58) | Incorporate / supersede | Include the verified service; normalize its description and ordering. [Source](https://xurl.app). |
| [#59](https://github.com/738/awesome-url-shortener/pull/59) | Incorporate / supersede | Include Pxl; official URL-shortener API documentation confirms shortening. Do not make an independent GDPR-compliance assertion. [Source](https://www.pxl.to/blog/url-shortener-api). |
| [#62](https://github.com/738/awesome-url-shortener/pull/62) | Incorporate / supersede | Include the verified service; normalize its description and ordering. [Source](https://qryptic.io). |
| [#63](https://github.com/738/awesome-url-shortener/pull/63) | Incorporate / supersede | Include Lua.sh with a direct source repository link. [Source](https://github.com/luadotsh/lua). |
| [#65](https://github.com/738/awesome-url-shortener/pull/65) | Incorporate / supersede | Include the verified service; normalize its description and ordering. [Source](https://yolla.link). |
| [#67](https://github.com/738/awesome-url-shortener/pull/67) | Incorporate / supersede | Include the verified service; normalize its description and ordering. [Source](https://s.ee). |
| [#69](https://github.com/738/awesome-url-shortener/pull/69) | Incorporate / supersede | Include MyURL with a neutral description. Homepage and public JavaScript bundle describe URL shortening; browser execution was not verified. [Source](https://myurlsh.de/). |
| [#71](https://github.com/738/awesome-url-shortener/pull/71) | Incorporate / supersede | Include the verified service; normalize its description and ordering. [Source](https://prettyurl.net). |
| [#75](https://github.com/738/awesome-url-shortener/pull/75) | Incorporate / supersede | Include Minily; paid plans are required for unlimited links and custom domains. [Source](https://minily.org/). |
| [#78](https://github.com/738/awesome-url-shortener/pull/78) | Hold open | urls.ac failed DNS resolution on repeated checks. Supply a reachable replacement URL. [Source](https://urls.ac). |
| [#79](https://github.com/738/awesome-url-shortener/pull/79) | Close without inclusion | Do not include: link-rotator.com currently shows a parked domain / possible sale page. [Source](https://link-rotator.com/). |
| [#81](https://github.com/738/awesome-url-shortener/pull/81) | Incorporate / supersede | Include ShortPen without the unsupported promise of free service without limits. [Source](https://shortpen.com/). |
| [#106](https://github.com/738/awesome-url-shortener/pull/106) | Incorporate / supersede | Include Zu.lk with a concise feature description, without promotional claims. [Source](https://zu.lk). |
| [#107](https://github.com/738/awesome-url-shortener/pull/107) | Incorporate / supersede | Include PyMD without claiming Python Software Foundation endorsement; retain the existing sor.bz entry. Do not add pork.li, which failed DNS resolution. [Source](https://py.md/). |
| [#108](https://github.com/738/awesome-url-shortener/pull/108) | Hold open | ogli.sh returned HTTP 520 on repeated checks. Supply a working service or documented replacement. [Source](https://ogli.sh). |
| [#111](https://github.com/738/awesome-url-shortener/pull/111) | Hold open | url-shortener.co.in now serves a logistics business. TS4 only exposed a JavaScript application shell in this review. Remove the unrelated domain and provide a verifiable shortening page for TS4. [Source](https://url-shortener.co.in). |
| [#112](https://github.com/738/awesome-url-shortener/pull/112) | Incorporate / supersede | Include kua.lat with a factual feature description instead of its slogan. [Source](https://kua.lat). |
| [#113](https://github.com/738/awesome-url-shortener/pull/113) | Incorporate / supersede | Include Linkly and verified status corrections. Buffer and Ow.ly remain available in their parent products; Polr is not archived. reduced.to is archived, not actively continuing as claimed. [Source](https://support.buffer.com/en-us/articles/shortening-and-unshortening-links-dgev2p41yY). |
| [#118](https://github.com/738/awesome-url-shortener/pull/118) | Hold open | The repository and PHP entry point contain no identifiable open-source license. Add an explicit license before inclusion in the open-source section. [Source](https://github.com/dayeggpi/CutItOff). |
| [#120](https://github.com/738/awesome-url-shortener/pull/120) | Incorporate / supersede | Include the verified service; normalize its description and ordering. [Source](https://replug.io/). |
| [#121](https://github.com/738/awesome-url-shortener/pull/121) | Incorporate / supersede | Include Rushomon with a direct link to its AGPL source repository. [Source](https://rushomon.cc). |
| [#124](https://github.com/738/awesome-url-shortener/pull/124) | Hold open | The current homepage and API documentation list utility endpoints but no URL-shortening endpoint. Supply current shortening documentation. [Source](https://api-snap.com/docs). |
| [#126](https://github.com/738/awesome-url-shortener/pull/126) | Hold open | linkshrink.dev failed DNS resolution on repeated checks. Supply a reachable service URL before inclusion. [Source](https://linkshrink.dev). |
| [#128](https://github.com/738/awesome-url-shortener/pull/128) | Incorporate / supersede | Include Brevio; its README explicitly declares MIT licensing and provides installation instructions. [Source](https://github.com/numanrki/Brevio). |
| [#133](https://github.com/738/awesome-url-shortener/pull/133) | Incorporate / supersede | Include PeakURL as self-hosted open-source software; replace the promotional description. [Source](https://peakurl.org/open-source). |
| [#134](https://github.com/738/awesome-url-shortener/pull/134) | Incorporate / supersede | Include the verified service; normalize its description and ordering. [Source](https://www.capsulink.com). |
| [#135](https://github.com/738/awesome-url-shortener/pull/135) | Incorporate / supersede | Include the verified service; normalize its description and ordering. [Source](https://redirhub.com). |
| [#136](https://github.com/738/awesome-url-shortener/pull/136) | Incorporate / supersede | Include the shared-provider relationship confirmed by the v.gd FAQ. [Source](https://v.gd/faq.php). |
| [#137](https://github.com/738/awesome-url-shortener/pull/137) | Incorporate / supersede | Do not add the stale 10-free-links/month claim. Link to current pricing and trial terms. [Source](https://t.ly/pricing). |
| [#138](https://github.com/738/awesome-url-shortener/pull/138) | Incorporate / supersede | Include 5 free links/month with an official source and verification date. [Source](https://bitly.com/pages/pricing). |
| [#139](https://github.com/738/awesome-url-shortener/pull/139) | Incorporate / supersede | Include 30 free links/month with an official source and verification date. [Source](https://cutt.ly/resources/tools/url-shortener). |
| [#140](https://github.com/738/awesome-url-shortener/pull/140) | Incorporate / supersede | Do not mark Ow.ly deprecated. Hootsuite still documents it as a dashboard feature; link to that page. [Source](https://www.hootsuite.com/pages/owly). |
| [#141](https://github.com/738/awesome-url-shortener/pull/141) | Incorporate / supersede | Record the current HTTPS failure separately from confirmed discontinued services. [Source](https://rip.to/). |
| [#142](https://github.com/738/awesome-url-shortener/pull/142) | Incorporate / supersede | Record current HTTP 403 as an access problem, not proof of permanent shutdown. [Source](https://bitly.kr/). |
| [#143](https://github.com/738/awesome-url-shortener/pull/143) | Incorporate / supersede | Include the anonymous-link expiration note supported by tiny.cc. [Source](https://tiny.cc/). |
| [#144](https://github.com/738/awesome-url-shortener/pull/144) | Incorporate / supersede | Include x.gd with optional expiration; avoid an unconditional promise that links never expire. [Source](https://x.gd). |
| [#145](https://github.com/738/awesome-url-shortener/pull/145) | Incorporate / supersede | Selectively incorporate sorting, descriptions, restored 3.ly, and verified status changes. Keep Ow.ly, Buffer, Polr, and shorten-url.com; do not repeat unsupported shutdown or archive claims. Preserve LinkHuddle because a waitlist alone does not establish shutdown. [Source](https://www.hootsuite.com/pages/owly). |
| [#148](https://github.com/738/awesome-url-shortener/pull/148) | Incorporate / supersede | Include the verified service; normalize its description and ordering. [Source](https://urlyte.com). |
| [#151](https://github.com/738/awesome-url-shortener/pull/151) | Incorporate / supersede | Include mnlc.es using its current misenlac.es homepage; normalize formatting. [Source](https://misenlac.es/es). |
| [#154](https://github.com/738/awesome-url-shortener/pull/154) | Incorporate / supersede | Include under a separate commercial self-hosted category, not hosted services or open-source software. [Source](https://gempixel.com/products/premium-url-shortener). |
| [#157](https://github.com/738/awesome-url-shortener/pull/157) | Incorporate / supersede | Include Flyn with free and paid plans; custom domains and deep links are not free-plan features. [Source](https://www.flyn.to/). |
| [#159](https://github.com/738/awesome-url-shortener/pull/159) | Incorporate / supersede | Include under self-hosted software; clarify destination allowlist and optional aggregate analytics instead of claiming no tracking. [Source](https://github.com/kaikayy/tab-share-shortener). |
| [#161](https://github.com/738/awesome-url-shortener/pull/161) | Incorporate / supersede | Include FavURL; feature page confirms analytics, QR codes, collections, and custom domains. [Source](https://fav-url.com/features). |

## Issues

| Issue | Proposed action | Reason and evidence |
| --- | --- | --- |
| [#25](https://github.com/738/awesome-url-shortener/issues/25) | Close as completed | rip.to was already added in merged PR #29 on 2024-01-15. This review separately records its current access failure. [Source](https://github.com/738/awesome-url-shortener/pull/29). |
| [#38](https://github.com/738/awesome-url-shortener/issues/38) | Incorporate / close | Original repository is 404; the replacement repository has MIT licensing and self-hosting instructions. [Source](https://github.com/vaginessa/Twin-Url). |
| [#39](https://github.com/738/awesome-url-shortener/issues/39) | Incorporate / close | Include URLed in the archived-projects category, not as an actively maintained project. [Source](https://github.com/masoncfrancis/urled). |
| [#60](https://github.com/738/awesome-url-shortener/issues/60) | Incorporate / close | Include link2.it; the current homepage provides a shortening form. [Source](https://link2.it). |
| [#61](https://github.com/738/awesome-url-shortener/issues/61) | Incorporate / close | gg.gg now shows a Good Game placeholder instead of its former shortening service. [Source](https://gg.gg). |
| [#64](https://github.com/738/awesome-url-shortener/issues/64) | Hold open | Smally failed DNS resolution on repeated live checks. Search results contain an older page, so restoration or a working replacement is needed. [Source](https://smally.cc). |
| [#73](https://github.com/738/awesome-url-shortener/issues/73) | Incorporate / close | wr.do redirects to LikeDo; include the current product and identify its former name. [Source](https://like.do). |
| [#77](https://github.com/738/awesome-url-shortener/issues/77) | Incorporate / close | Remove from active services; the operator confirmed public access was disabled even though the website still loads. [Source](https://73.nu/shutdown-notice). |
| [#114](https://github.com/738/awesome-url-shortener/issues/114) | Incorporate / close | Move zlnk.com out of active services; the domain now leads to an Afternic sale listing. [Source](https://www.afternic.com/domain/zlnk.com). |

## Additional evidence for overlapping cleanup PRs

- [Kutt upstream warning](https://github.com/thedevs-network/kutt#readme): kutt.it is no longer owned by the project; the current service is [kutt.to](https://kutt.to).
- [Buffer help](https://support.buffer.com/en-us/articles/shortening-and-unshortening-links-dgev2p41yY) and [Hootsuite Ow.ly](https://www.hootsuite.com/pages/owly) document active built-in shortening.
- [Polr source](https://github.com/cydrobolt/polr) is accessible and not marked archived; the archive claim in #113 is unsupported.
- [reduced.to source](https://github.com/origranot/reduced.to) is marked archived on 2025-04-27.
- [lstu.fr](https://lstu.fr/login) explicitly restricts shortening to its owner; the self-hosted project remains available.
- [clicky.me](https://clicky.me) explicitly says it is in maintenance mode and cannot be actively used.
- [3.ly](https://www.3.ly/) currently offers a shortener and is restored to the active list.
- [shorten-url.com](https://shorten-url.com/en) still displays a service and plans; a sale notice alone does not establish shutdown.

## Attribution

The proposal builds on the linked original contributions. Their PR links preserve the individual change history. Original proposals are described as superseded, not merged, if this consolidated update is accepted.
