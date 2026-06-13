# TuneIn

TuneIn is an internet radio and podcast platform providing APIs for accessing live radio stations, sports audio, news, podcasts, and searching audio content worldwide. TuneIn exposes three distinct API surfaces:

1. **OPML Streaming API** (`opml.radiotime.com`) — browse categories, search stations, describe content, and retrieve stream URLs. Freely accessible with optional partnerId for higher quotas. Responses available in OPML (XML) or JSON.

2. **AIR Broadcaster API** (`air.radiotime.com`) — allows licensed radio stations to push real-time now-playing metadata (title, artist, album, commercial flag) to TuneIn. Requires broadcaster credentials obtained via `tuneinonair@tunein.com`.

3. **Platform API** (`developer.tunein.com`) — full OAuth 2.0 REST API for OEM and smart-device partners embedding TuneIn into products. Provides categories, profiles, media, recommendations, favorites, and reporting. Requires a signed partner agreement and certification.

**Base URLs:**
- Streaming API: `https://opml.radiotime.com`
- AIR API: `http://air.radiotime.com`
- Platform API: `https://developer.tunein.com`

**Status:** https://status.tunein.com/

**Developer Portal:** https://developer.tunein.com/cfp_login

**Broadcaster API:** https://tunein.com/broadcasters/api/

**GitHub:** https://github.com/tunein

---

*APIs.json profile maintained by [API Evangelist](https://apievangelist.com).*
