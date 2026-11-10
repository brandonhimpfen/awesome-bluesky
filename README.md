# Awesome Bluesky [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for the Bluesky API, AT Protocol (atproto) Lexicons, Jetstream firehose listeners, custom feed generators, bot frameworks, OAuth2 authentication, and decentralized social tooling.

Bluesky is a decentralized social networking application built on the AT Protocol (Authenticated Transfer Protocol), an open, federated standard for large-scale social applications. Programmatic development within the Bluesky ecosystem encompasses interacting with Personal Data Servers (PDS), building custom algorithmic feeds, streaming real-time network events via Jetstream and Relays, operating custom labelers, and managing federated user identities (DIDs and handles). This list is intended for decentralized web developers, social protocol engineers, bot authors, algorithmic feed creators, and open web researchers.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Official Protocols & Platform Core](#official-protocols--platform-core)
- [API SDKs & Client Libraries](#api-sdks--client-libraries)
  - [TypeScript & JavaScript](#typescript--javascript)
  - [Python, Go & Rust](#python-go--rust)
  - [Other Languages](#other-languages)
- [Firehose, Jetstream & Event Streams](#firehose-jetstream--event-streams)
- [Feed Generators & Labelers](#feed-generators--labelers)
- [Bot Frameworks & Developer Tooling](#bot-frameworks--developer-tooling)
- [Related Awesome Lists](#related-awesome-lists)

## Official Protocols & Platform Core

Core protocol specifications, reference implementations, lexicon schemas, and architectural standards powering AT Protocol.

- [AT Protocol Architecture](https://atproto.com/) — Official documentation covering DIDs, repository data structures, XRPC HTTP APIs, and federated PDS topologies.
- [indigo](https://github.com/bluesky-social/indigo) — Official Go reference implementation of AT Protocol services, including PDS and Relay infrastructure.
- [atproto Monorepo](https://github.com/bluesky-social/atproto) — Official TypeScript reference implementation of AT Protocol core packages, lexicons, and dev server tooling.
- [Ozone](https://github.com/bluesky-social/ozone) — Official collaborative moderation and labeling service designed for AT Protocol network operators.

## API SDKs & Client Libraries

Language-native wrappers for handling XRPC requests, session management, OAuth2 PKCE flows, and rich-text parsing.

### TypeScript & JavaScript

- [@atproto/api](https://www.npmjs.com/package/@atproto/api) — Official TypeScript API client providing complete typed schemas, session managers, and rich-text utilities.
- [@atproto/oauth-client-browser](https://github.com/bluesky-social/atproto) — Official OAuth2 client package for implementing secure user login in web applications.
- [trotsky](https://github.com/pirhoo/trotsky) — Type-safe JavaScript library for building automated workflows on top of AT Protocol APIs.

### Python, Go & Rust

- [atproto Python SDK](https://github.com/MarshalX/atproto) — High-level Python library supporting synchronous/asynchronous API clients, session auto-refresh, and record parsing.
- [atrium](https://github.com/sugyan/atrium) — Modular, pure Rust implementation of AT Protocol services and Lexicon types.
- [botsky](https://github.com/davhofer/botsky) — Lightweight Go client tailored specifically for writing automated Bluesky bots.

### Other Languages

- [FishyFlip](https://github.com/fishyflip/fishyflip) — Full-featured .NET C# class library for interacting with AT Protocol and Bluesky endpoints.
- [atproto.dart](https://github.com/my-swr/atproto.dart) — Dart and Flutter SDK suite for building cross-platform mobile apps on AT Protocol.
- [ATproto Ruby SDK](https://github.com/snood1205/atproto) — Ruby gem suite for interacting with Bluesky APIs and handling XRPC calls.

## Firehose, Jetstream & Event Streams

Tools and lightweight proxies for subscribing to the global real-time stream of network updates.

- [Jetstream](https://github.com/bluesky-social/jetstream) — Official lightweight JSON firehose proxy translating raw CAR/CBOR event streams into simple WebSocket JSON payloads.
- [skyfall](https://github.com/sammikiv/skyfall) — Ruby gem for consuming and parsing events from the Bluesky AT Protocol firehose.
- [bluesky-firehose-py](https://github.com/ruggsea/bluesky-firehose-py) — Python library and CLI tool for capturing and archiving live network posts via Jetstream.

## Feed Generators & Labelers

Starter templates and frameworks for publishing custom algorithmic timelines and third-party moderation labels.

- [feed-generator](https://github.com/bluesky-social/feed-generator) — Official TypeScript template for running custom algorithmic feed generator services.
- [bsky-feedgen (Go)](https://github.com/aykhans/bsky-feedgen) — Go-based feed generator for parsing post streams and serving custom timeline APIs.
- [labeler](https://github.com/bluesky-social/atproto) — Lightweight alternative to Ozone for deploying and operating independent AT Protocol labelers.

## Bot Frameworks & Developer Tooling

Starter kits, local sandbox runners, and automation frameworks built for Bluesky.

- [bsky-event-handlers](https://github.com/bluesky-social/atproto) — Event-driven TypeScript framework designed for crafting modular Bluesky bots.
- [atproto-mcp](https://github.com/cameronrye/atproto-mcp) — Model Context Protocol (MCP) server giving LLMs direct read/write access to AT Protocol networks.
- [didkit](https://github.com/mackuba/didkit) — Developer utility for resolving and manipulating Decentralized Identifiers (DIDs) used across AT Protocol.
- [bluesky-post-action](https://github.com/my-swr/bluesky-post-action) — GitHub Action for automatically posting updates to Bluesky from CI/CD workflows.

## Related Awesome Lists

- [Awesome ActivityPub](https://github.com/brandonhimpfen/awesome-activitypub) — Decentralized social protocols, Mastodon server tools, and ActivityPub implementations.
- [Awesome Reddit](https://github.com/brandonhimpfen/awesome-reddit) — Reddit Data API, Devvit platform, PRAW, and community moderation bots.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Guidelines, licensing models, and project governance for open software repositories.
- [Awesome TypeScript](https://github.com/brandonhimpfen/awesome-typescript) — Type-safe web development, Node SDKs, and API client generation tools.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
