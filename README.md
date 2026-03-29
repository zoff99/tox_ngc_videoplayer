# Tox NGC Videoplayer

tox_ngc_videoplayer is a specialized C application for streaming high-quality synchronized audio and video over the Tox P2P protocol
to NGC (NewGroupChat) Tox Groups.

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![Liberapay](https://img.shields.io/liberapay/goal/zoff.svg?logo=liberapay)](https://liberapay.com/zoff/donate)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/zoff99/tox_ngc_videoplayer)

### Command Line Options Reference

#### Basic Options
| Option | Long Form | Argument | Description |
|--------|-----------|----------|-------------|
| `-h` | `--help` | None | Display help message and exit |
| `-v` | `--version` | None | Show version information  |

#### Input/Output Options
| Option | Argument | Description | Default |
|--------|----------|-------------|---------|
| `-i` | `<path>` | Input filename or "desktop" for screenshare  | Required |
| `-d` | `<display>` | X11 display number for desktop capture | `:0.0`  |
| `-p` | `<device>` | PulseAudio input device for desktop audio | `default`  |
| `-f` | `<fps>` | Capture FPS for desktop mode  | `30` |

#### Network Options
| Option | Argument | Description |
|--------|----------|-------------|
| `-t` | None | TCP-only mode (disable UDP)  |
| `-T` | None | Use Tor proxy (SOCKS5 on 127.0.0.1:9050) |

#### Quality Options
| Option | Argument | Description | Range |
|--------|----------|-------------|-------|
| `-r` | None | Enable VBR (Variable Bitrate) starting at 200 kbit/s  | N/A |
| `-m` | `<bitrate>` | Set maximum video bitrate | 100-8000 kbit/s |


<br>
Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.
<br>
No part of this work may be used or reproduced in any manner for the purpose of training artificial intelligence technologies or systems.
