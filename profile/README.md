# GarlicSignage
Modular open-source digital signage, built on the [SMIL](https://garlic-signage.com/resources/digital-signage-smil/) standard.

Garlic-player has been running on around 2000 screens in production since 2020.

Most component works on their own. Use one, combine a few, or run all of them.

- Use garlic-player with any SMIL 3.0 CMS
- Use garlic-hub with any SMIL 3.0 player
- No vendor lock-in, no forced cloud, no subscriptions

Just open infrastructure.

## The Components

| Project | What it does | Standalone | Platform |
| --- | --- | --- | --- |
| [garlic-player](https://github.com/garlic-signage/garlic-player) | SMIL media player | Yes, even from a USB stick | Linux, Android, macOS, Windows |
| [garlic-hub](https://github.com/garlic-signage/garlic-hub) | CMS & Device Management | Yes, exports standard SMIL | Self-hosted |
| [garlic-launcher](https://github.com/garlic-signage/garlic-launcher) | Root-free Android kiosk launcher | Needs an Android player | Android |
| [garlic-proxy](https://github.com/garlic-signage/garlic-proxy) | Proxy for restricted network environments | Optional | Self-hosted |
| [garlic-widgets](https://github.com/garlic-signage/garlic-widgets) | HTML5 widget library (W3C Packaged Web Apps) | Yes | HTML5 |
| [garlic-widgets-jetbrains](https://github.com/garlic-signage/garlic-widgets-jetbrains) | Widget development plugin | Yes | JetBrains |
| [garlic-widgets-vscode](https://github.com/garlic-signage/garlic-widgets-vscode) | Widget development plugin | Yes | VS Code |

In development: [garlic-analytics]((https://github.com/garlic-signage/garlic-hub)) (playback reporting for digital signage player)

## Why SMIL?
SMIL is what a broadcast schedule is to television: it defines what plays, when, and where. Not how it looks. It is [W3C standard](https://www.w3.org/TR/SMIL3/) since 1998 and vendor-neutral. SMIL was built to schedule and synchronize media across zones, playlists, and devices. [Not to render content](https://sagiadinos.com/articles/you-all-got-smil-wrong/).

The digital signage industry has spent decades reinventing this wheel behind proprietary walls. SMIL breaks that forced marriage between CMS and player, enabling open, interoperable infrastructure any vendor can build on. And it breaks the vendor lock-in that the industry profits from.

## License
Most projects are [AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0.html), some like the Widgets are MIT Licensed.  
All free to use. Fully open.

## Get Involved
- Bug reports and feature requests → Issues in the respective repo
- Questions → [Discussions](https://github.com/orgs/garlic-signage/discussions)
- Commercial support & custom development → [smil-control.com](https://smil-control.com)

Support the project → [GitHub Sponsors](https://github.com/sponsors/sagiadinos)

→ [garlic-signage.com](https://garlic-signage.com)
