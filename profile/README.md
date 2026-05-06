# GarlicSignage
A complete open-source digital signage stack, built on the 
[SMIL](https://garlic-signage.com/resources/digital-signage-smil/) standard.

- No vendor lock-in
- No forced cloud
- No subscriptions
- No black boxes

Just open infrastructure.

## The Stack

| Project | What it does | Platform |
|---|---|---|
| [garlic-player](https://github.com/garlic-signage/garlic-player) | SMIL media player | Linux, Android, macOS, Windows |
| [garlic-hub](https://github.com/garlic-signage/garlic-hub) | CMS & Device Management | Self-hosted |
| [garlic-launcher](https://github.com/garlic-signage/garlic-launcher) | Root-free Android kiosk launcher | Android |
| [garlic-daemon](https://github.com/garlic-signage/garlic-daemon) | systemd-based player maintenance (in development) | Linux |
| [garlic-proxy](https://github.com/garlic-signage/garlic-proxy) | Proxy for restricted network environments | Self-hosted |
| [garlic-widgets](https://github.com/garlic-signage/garlic-widgets) | Widget Library based on W3C Packedsites WEb | HTML5 |
| [garlic-widgets-jetbrains](https://...) | Widget development plugin | JetBrains |
| [garlic-widgets-vscode](https://...) | Widget development plugin | VS Code |

## Why SMIL?
SMIL is what a broadcast schedule is to television: it defines what plays, when, and where. Not how it looks. It is [W3C standard](https://www.w3.org/TR/SMIL3/) since 1998 and vendor-neutral. SMIL was built to schedule and synchronize media across zones, playlists, and devices. [Not to render content](https://sagiadinos.com/articles/you-all-got-smil-wrong/).

The digital signage industry has spent decades reinventing this wheel behind proprietary walls. SMIL breaks that forced marriage between CMS and player, enabling open, interoperable infrastructure any vendor can build on. And it breaks the vendor lock-in that the industry profits from.

## License
All projects are [AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0.html).  
Free to use. Fully open.

## Get Involved
- Bug reports and feature requests → Issues in the respective repo
- Questions → [Discussions](https://github.com/orgs/garlic-signage/discussions)
- Commercial support & custom development → [smil-control.com](https://smil-control.com)

Support the project → [GitHub Sponsors](https://github.com/sponsors/sagiadinos)

→ [garlic-signage.com](https://garlic-signage.com)
