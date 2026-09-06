# Third-party components

Velora uses unmodified external executables. Their notices are included beside each binary in engine/. No association with or endorsement by their authors is implied.

| Component | Version | License / corresponding source |
|---|---|---|
| Xray-core | 26.3.27 | MPL-2.0; https://github.com/XTLS/Xray-core/tree/v26.3.27 |
| sing-box | 1.14.0 | GPL-3.0-or-later and upstream additional terms; https://github.com/SagerNet/sing-box/tree/v1.14.0 |
| Wintun | Included in Xray release | See engine/sing-box/LICENSE-wintun.txt; https://git.zx2c4.com/wintun/ |
| Zapret / Flowseal scripts | 1.10.2 | MIT; https://github.com/Flowseal/zapret-discord-youtube/tree/1.10.2 and https://github.com/bol-van/zapret |
| WinDivert | Bundled upstream | LGPL-3.0 / GPL-2.0; https://github.com/basil00/WinDivert/tree/v2.2.2 |
| Cygwin runtime | Bundled upstream | GPL-3.0 with linking exception; https://cygwin.com/licensing.html and https://cygwin.com/packages/summary/cygwin-src.html |
| .NET Windows Desktop Runtime | 10.0 | MIT and third-party notices included in self-contained runtime; https://github.com/dotnet/runtime and https://github.com/dotnet/wpf |

Fix Internet executes winws directly using arguments from upstream strategy files; it does not run upstream service/update batch commands. Bundled domain lists cover YouTube and Discord. The broad IP-set strategy is disabled by a documentation-only IP range. User domain additions live separately in LocalAppData/Velora/zapret-lists.

Pinned original release download addresses and SHA256 checksums are in scripts/prepare-engines.ps1. Source archives and build instructions are available at the corresponding upstream version links above.
