# Awesome URL Shortener

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A curated directory of URL shorteners, branded-link tools, and software you can host yourself.

Use a hosted service to get started, run your own shortener to manage the redirects yourself, or look up a service that has moved or closed.

**Directory review:** [September 21, 2026](BACKLOG_REVIEW.md). The review covers public pages, documentation, and access checks; it is not an end-to-end test of every service.

## Find What You Need

| Browse | Entries | What you will find |
| --- | ---: | --- |
| [Hosted services](#url-shortener-services) | 57 | Services for creating and managing short links without running a server. |
| [Self-hosted open source](#self-hosted-open-source-software) | 20 | Source code and tools for running your own shortener. |
| [Commercial self-hosted software](#commercial-self-hosted-software) | 1 | Paid software you install on your own infrastructure. |
| [Service history and access problems](#service-history-and-access-problems) | 22 | Archived projects, closed or restricted services, and dated access failures. |

Entries are alphabetical within each category. Some projects appear in both hosted and self-hosted sections.

## Before You Choose

* **Your domain:** Check custom-domain support and whether you can export your links if you move to another provider.
* **Link lifetime:** Check expiration rules and what happens when a free trial or subscription ends.
* **Plan limits:** Compare link creation limits, analytics retention, and API access. Features and pricing can change.
* **Hosting:** For self-hosted software, check the license, deployment instructions, and recent maintenance before installing.

## URL Shortener Services

Hosted tools for shortening, branding, and tracking links. Some require an account or a subscription; buff.ly and Ow.ly are features of Buffer and Hootsuite.

* [3.ly](https://www.3.ly/) - URL shortener with custom aliases, QR codes, and click statistics.
* [bit.ly](https://bitly.com) - URL shortener with a free plan limited to 5 links per month ([pricing](https://bitly.com/pages/pricing), checked 2026-09-21).
* [bl.ink](https://www.bl.ink) - Branded link management service.
* [buff.ly](https://buffer.com) - Link shortening available within Buffer ([usage guide](https://support.buffer.com/en-us/articles/shortening-and-unshortening-links-dgev2p41yY)).
* [Capsulink](https://www.capsulink.com) - URL shortener with smart redirects and QR codes.
* [cutt.ly](https://cutt.ly) - URL shortener with a free plan limited to 30 links per month ([plan details](https://cutt.ly/resources/tools/url-shortener), checked 2026-09-21).
* [Dub.co](https://dub.co) - Link management and attribution platform.
* [FavURL](https://fav-url.com/) - URL shortener with analytics, QR codes, link collections, and custom domains.
* [Flyn](https://www.flyn.to) - URL shortener with branded domains, click analytics, QR codes, and deep links; free and paid plans.
* [han.gl](https://han.gl) - Korean URL shortening service.
* [is.gd](https://is.gd) - URL shortening service with custom aliases.
* [kes.im](https://kes.im) - Ad-free URL shortener built on Cloudflare Workers.
* [kua.lat](https://kua.lat) - URL shortener with branded links, analytics, QR codes, and bio pages.
* [KurzeLinks.de](https://kurzelinks.de) - Link shortener based in Germany.
* [Kutt](https://kutt.to) - URL shortener with custom domains and link statistics.
* [LikeDo (formerly wr.do)](https://like.do) - URL shortener with custom aliases, password protection, and analytics.
* [link2.it](https://link2.it) - URL shortener with custom aliases, passwords, and link expiration.
* [LinkHuddle](https://linkhuddle.com/) - Huddle multiple links in one link.
* [Linkly](https://linklyhq.com) - URL shortener with custom domains, QR codes, and location-based redirects.
* [LinkSplit](https://linksplit.io/url-shortener) - URL shortening and traffic splitting service.
* [Minily](https://minily.org) - URL shortener with analytics and QR codes; custom domains and unlimited links require a paid plan.
* [mnlc.es](https://misenlac.es) - URL shortener with link-in-bio pages, QR codes, and analytics.
* [MyURL](https://myurlsh.de) - URL shortening service with a German-language interface.
* [name.com](https://www.name.com/branded-url-shortener) - Branded URL shortener powered by BL.INK.
* [oe.cd](https://oe.cd/) - Only OECD-related URLs can be shortened on this website.
* [Ow.ly](https://www.hootsuite.com/pages/owly) - Link shortening available within the Hootsuite dashboard.
* [prettyurl.net](https://prettyurl.net) - URL shortener with custom domains.
* [Pxl](https://www.pxl.to/) - URL shortener with QR codes, microsites, and retargeting pixels.
* [PyMD](https://py.md) - Community-maintained URL shortener for Python links.
* [qryptic.io](https://qryptic.io) - Link management service with URL shortening and QR codes.
* [rebrandly.com](https://rebrandly.com) - Branded URL shortening service.
* [RedirHub](https://www.redirhub.com) - URL shortening and redirect service with custom domains, HTTPS, analytics, and an API.
* [replug.io](https://replug.io/) - URL shortener with branded links, analytics, and bio pages.
* [s.ee](https://s.ee) - URL shortener with custom domains and analytics.
* [short.io](https://short.io) - URL shortener with custom domains and analytics.
* [shorten-url.com](https://shorten-url.com) - URL shortening service with multilingual support.
* [ShortPen](https://shortpen.com) - Link tracking service with short links, QR codes, and conversion analytics.
* [shorturl.at](https://www.shorturl.at) - URL shortening service.
* [SimpleURL](https://www.simpleurl.tech/) - URL shortener with branded links, QR codes, and analytics.
* [smallseotools](https://smallseotools.com/url-shortener) - Online URL shortening tool.
* [sor.bz](https://sor.bz) - Customizable URL shortener powered by PyMD.
* [spoo.me](https://spoo.me/) - URL shortener with custom links and click analytics.
* [switchy.io](https://switchy.io) - URL shortener with link tracking and retargeting.
* [T.LY](https://t.ly) - URL shortener with custom domains and analytics; see current [plans and trial terms](https://t.ly/pricing).
* [T2M](https://t2mio.com) - Link management service with branded URLs and QR codes.
* [tinu.be](https://tinu.be) - URL shortener and QR code generator.
* [Tiny URL](https://tiny.cc) - URL shortener; anonymous links can expire, while registering an account prevents expiration.
* [url1.io](https://url1.io) - URL shortener with custom links, QR codes, and analytics.
* [urlr.me](https://urlr.me/en) - URL shortener with API access.
* [URLyte](https://urlyte.com) - URL shortener with branded namespaces, click analytics, and QR codes.
* [v.gd](https://v.gd) - URL shortener from the same provider as is.gd.
* [vo.la](https://vo.la/) - Korean URL shortening service.
* [x.gd](https://x.gd) - Japanese URL shortening service with custom aliases and optional expiration.
* [xUrl.app](https://xurl.app) - URL shortening and file sharing service.
* [yaso.su](https://yaso.su/) - URL shortening service.
* [yolla.link](https://yolla.link) - URL shortener with analytics and QR code generation.
* [Zu.lk](https://zu.lk) - URL shortener with analytics, QR codes, and an MCP integration.

## Self-Hosted Open-Source Software

Run the shortener on infrastructure you manage. Follow each project's installation guide for its requirements and deployment options.

* [Brevio](https://github.com/numanrki/Brevio) - Self-hosted URL shortener with analytics, QR codes, bio pages, and deep links.
* [Dub.co](https://dub.co) - Open-source link management infrastructure.
* [Eastlake](https://github.com/Likenttt/eastlake-cloudflare-worker-short-url) - A URL shortener built on Cloudflare Workers.
* [Jinx.fyi](https://github.com/gdmcdonald/jinx) - Static URL shortener for GitHub Pages with a searchable link directory and QR codes.
* [kes.im](https://github.com/ramesaliyev/kes.im) - URL shortener built on Cloudflare Workers.
* [Kutt](https://github.com/thedevs-network/kutt) - Self-hosted URL shortener with custom domains, link statistics, and an API.
* [lstu](https://framagit.org/fiat-tux/hat-softwares/lstu/) - Self-hosted URL shortener written in Perl.
* [Lua.sh](https://github.com/luadotsh/lua) - Self-hosted URL shortener with custom domains and analytics.
* [PeakURL](https://peakurl.org) - Self-hosted URL shortener with custom aliases, QR codes, analytics, and an API.
* [Polr](https://polrproject.org) - Self-hosted URL shortener with custom branding and an API.
* [pygmy](https://github.com/amitt001/pygmy) - Extensible URL shortener with analytics written in Python.
* [Rushomon](https://github.com/piffio/rushomon) - Self-hosted URL shortener built with Rust and WebAssembly for Cloudflare Workers.
* [san.aq](https://github.com/neutronscott/sanaq) - URL shortener with an HTTP API usable with curl.
* [shlink](https://shlink.io) - Self-hosted URL shortener with visitor statistics.
* [shrtnr](https://github.com/oddbit/shrtnr) - Self-hosted URL shortener on Cloudflare Workers and D1 with click analytics, an admin dashboard, and a built-in MCP server.
* [Sink](https://github.com/miantiao-me/Sink) - URL shortener with analytics running on Cloudflare.
* [Slug](https://github.com/pheralb/slug) - Self-hosted URL shortener built with the T3 Stack.
* [Tab Share Shortener](https://github.com/kaikayy/tab-share-shortener) - Self-hosted Node.js or Cloudflare Worker shortener with a destination allowlist, link expiration, and optional aggregate analytics.
* [Twin-Url](https://github.com/vaginessa/Twin-Url) - Self-hosted URL shortener built on Cloudflare Workers and KV.
* [yourls](https://yourls.org) - Self-hosted URL shortener with an extensible plugin system.

## Commercial Self-Hosted Software

Paid software for installation on your own server.

* [Premium URL Shortener](https://gempixel.com/products/premium-url-shortener) - Commercial self-hosted software with link-in-bio pages and QR codes.

## Service History and Access Problems

Looking for an old service? These records explain where it went and distinguish confirmed changes from access failures.

### Archived Open-Source Projects

Archived repositories, kept here for reference.

<details>
<summary>View 3 archived projects</summary>

* [Pckd](https://github.com/Just-Moh-it/Pckd) - Self-hosted URL shortener; repository archived.
* [reduced.to](https://github.com/origranot/reduced.to) - Self-hosted URL shortener with analytics; repository archived on 2025-04-27.
* [URLed](https://github.com/masoncfrancis/urled) - Lightweight self-hosted URL shortener written in Go; repository archived.

</details>

### Deprecated or Restricted Services

Services previously listed as deprecated, plus confirmed shutdowns, domain changes, and restrictions on public access.

<details>
<summary>View 14 deprecated or restricted services</summary>

* [73.nu](https://73.nu/shutdown-notice) - Public service shut down; see the operator announcement.
* [clicky.me](https://clicky.me) - In maintenance mode; the site states that it can no longer be actively used.
* [cutit.org](https://cutit.org) - Website suspended.
* [gg.gg](https://gg.gg) - Former shortener replaced by a Good Game placeholder page.
* [git.io](https://git.io) - GitHub stopped accepting new links on 2022-01-11.
* [goo.gl](https://goo.gl) - Google announced deprecation on 2018-03-30.
* [hoy.kr](https://hoy.kr/) - Previously listed as deprecated.
* [kutt.it](https://github.com/thedevs-network/kutt#readme) - Former domain is no longer owned by the Kutt project; use kutt.to or the self-hosted project.
* [LiveChat URL shortener](https://www.livechatinc.com/url-shortener/) - Former shortener page now redirects to a UTM builder.
* [lstu.fr](https://lstu.fr) - Public shortening restricted to the site owner; self-hosted software remains available.
* [me2.do](https://me2.do) - Deprecated by Naver on 2016-08-18.
* [s2r.co](https://s2r.co) - Previously listed as deprecated.
* [soo.gd](https://soo.gd/) - Previously listed as deprecated.
* [zlnk.com](https://www.afternic.com/domain/zlnk.com) - Former shortener domain listed for sale.

</details>

### Services with Access Problems

Observed on 2026-09-21. These access failures do not establish permanent shutdown.

<details>
<summary>View 5 services with access problems</summary>

* [bitly.kr](https://bitly.kr) - Homepage returned HTTP 403 during this review; shutdown not confirmed.
* [fox.ly](https://foxlyme.com/) - Listed homepage returned a Wix domain-connection error and HTTP 404 during this review; shutdown not confirmed.
* [reduced.to](https://reduced.to) - Hosted endpoint failed TLS validation during this review; archived source is listed above.
* [rip.to](https://rip.to) - HTTPS connection failed during this review; shutdown not confirmed.
* [san.aq](https://san.aq) - HTTPS certificate expired during this review; self-hosted source remains available.

</details>

## Contributing

* **Add a shortener:** Read the [contribution guidelines](CONTRIBUTING.md), check for an existing entry or suggestion, and submit one service per pull request.
* **Update an entry:** [Open an issue](https://github.com/738/awesome-url-shortener/issues/new) or a pull request with the corrected link or description. Include an official source or the date and details of an access problem.

Keep descriptions brief and factual, and update the category counts when adding or moving an entry. Use the same format as the list:

```markdown
* [Service name](https://example.com) - A short description ending with a period.
```

## License

[MIT](LICENSE).
