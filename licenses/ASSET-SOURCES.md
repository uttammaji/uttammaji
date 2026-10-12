# Asset sources and licences

## Fonts (embedded as base64 WOFF2 subsets inside each SVG)
| Font | Role | Licence | Source |
| --- | --- | --- | --- |
| Unbounded (variable, wght) | display | SIL Open Font License 1.1 (`OFL-Unbounded.txt`) | https://github.com/google/fonts/tree/main/ofl/unbounded |
| JetBrains Mono (variable, wght) | mono | SIL Open Font License 1.1 (`OFL-JetBrainsMono.txt`) | https://github.com/google/fonts/tree/main/ofl/jetbrainsmono |

Both were subset (Basic Latin plus a few punctuation marks) with fontTools `pyftsubset` and converted to WOFF2. They are referenced inside the SVGs under internal aliases; the font files are not distributed separately.

## Brand icons
Marks are the official Simple Icons paths (https://simpleicons.org), whose icon data is released under CC0 1.0 (`SIMPLE-ICONS-LICENSE.md`). The brands themselves remain trademarks of their owners and are used only to refer to the technologies/platforms.

| Icons | Simple Icons release |
| --- | --- |
| Node.js, Express, JavaScript, PostgreSQL, MongoDB, MySQL, Linux, Docker, Git, GitHub, Jenkins, LinkedIn | simple-icons 13.21.0 (npm) |
| AWS (`amazonaws`) | simple-icons 11.14.0 (npm). It was removed from later Simple Icons releases, so the last release that carries it was used. |

LinkedIn was also removed from newer Simple Icons releases; the 13.21.0 mark is used.

## Photos
Supplied by the profile owner: `mypic.jpeg`, `my3.jpeg`, `my2.jpeg`. Only rectangular crops (black letterbox bars removed), resizing and JPEG re-encoding were applied. Nothing was redrawn, retouched or masked. Rounded corners are a plain rounded-rectangle clip, not a subject silhouette.

## Data
GitHub snapshot (22 public repositories, 6 followers, 4 following, 2 achievements: Quickdraw, Pull Shark; GitHub user id 181652008) read from https://github.com/uttammaji on 12 Oct 2026. Project text comes from the owner's existing profile README.
