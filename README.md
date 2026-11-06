<div align="center">

![DiskVision Ultra — Your files. Finally visible.](assets/hero.svg)

### The future of looking at files is already installed.

[![Platform](https://img.shields.io/badge/platform-Windows-8ab4ff?style=for-the-badge&labelColor=131722)](#compatibility)
[![Dependencies](https://img.shields.io/badge/dependencies-0-7ce8bf?style=for-the-badge&labelColor=131722)](#installation)
[![AI](https://img.shields.io/badge/AI-absolutely%20not-c4a5ff?style=for-the-badge&labelColor=131722)](#frequently-anticipated-questions)
[![License](https://img.shields.io/badge/license-MIT-ffcc85?style=for-the-badge&labelColor=131722)](LICENSE)

**[Quick start](#quick-start)** · **[Architecture](#architecture)** · **[Editions](#choose-your-edition)** · **[Nederlands](docs/NEDERLANDS.md)**

*Enterprise vocabulary. Household functionality.*

</div>

---

## A new era of directory awareness

For too long, files have existed inside folders without a dedicated product launch.

**DiskVision Ultra™** brings unprecedented visibility to the contents of your current directory. Discover filenames. Observe folders. Experience the profound reassurance that your documents are, in fact, somewhere.

No installer. No account. No subscription. No executable in this repository.

> **This is a parody product page.** The entire “tool” consists of the built-in directory-listing commands below (plus a premium alias). They list the current folder; they do not analyse disk usage or scan your entire drive.

## Quick start

### Modern Experience Edition

Open PowerShell in the folder you want to inspect:

```powershell
Get-ChildItem
```

### Legacy Enterprise Edition

Open Command Prompt in the folder you want to inspect:

```cmd
dir
```

### Pro Edition

*Less typing. Same files.*

```powershell
gci
```

`gci` is PowerShell’s built-in alias for `Get-ChildItem`. Three characters instead of twelve: **75% fewer typed characters**, with exactly the same functionality. This is a typing reduction, not a runtime speed claim.

> We didn’t improve the command. We shortened the journey.

That is the complete product. You have finished onboarding.

## Why DiskVision Ultra?

| Capability | The breakthrough |
| :--- | :--- |
| **Directory intelligence** | Lists the contents of the current folder. |
| **Human-readable observability** | Filenames appear as text. On your screen. |
| **Local-first execution** | The commands run on your computer. Remote folders still require a network connection. |
| **Zero additional dependencies** | Uses the command shell you already have. |
| **Frictionless deployment** | There is nothing to deploy. |
| **Agent-free architecture** | No background service. No model. No suspiciously busy tray icon. |
| **Bring your own files** | You already did. |

## Architecture

```mermaid
flowchart LR
    A[You] --> B{Strategic shell selection}
    B -->|Modern Experience| C[Get-ChildItem]
    B -->|Legacy Enterprise| D[dir]
    B -->|Pro Edition| P[gci]
    P --> C
    C --> E[Current folder]
    D --> E
    E --> F[Names on a screen]
    F --> G[Unprecedented clarity]
```

<div align="center">

*Eight diagram nodes of value. Two commands. One premium alias.*

</div>

## Choose your edition

| | Modern Experience | Legacy Enterprise | Pro |
| :--- | :---: | :---: | :---: |
| Underlying technology | PowerShell | Command Prompt | Still PowerShell |
| Command | `Get-ChildItem` | `dir` | `gci` |
| Lists files and folders | ✓ | ✓ | ✓, professionally |
| Output | PowerShell objects, displayed as a table | Text | The same PowerShell objects |
| Typed characters | 12 | 3 | 3, but premium |
| Additional installation | None, when PowerShell is available | None, when CMD is available | None, again |
| Mandatory cloud account | No | No | Absolutely not |
| Monthly fee | €0 | €0, but with more gravitas | €0 Pro Max |
| Premium support | Read the command again | Read the shorter command again | We saved you nine characters |

All editions use their shell’s default behaviour. Formatting and the items shown can differ between shells. Hidden/system items are not guaranteed to appear. None of the listing commands above performs a recursive scan.

## Installation

<details>
<summary><strong>Expand the complete installation procedure</strong></summary>

You may close this section. Installation is complete.

</details>

## Performance

We removed the application to reduce application overhead.

No benchmarks were performed. Listing time depends on the directory, filesystem, permissions and storage connection. The charts were cancelled when someone asked what they would measure.

## Roadmap

- [x] Display filenames
- [x] Support folders containing files
- [x] Add a second command and call it an edition
- [x] Commission a banner larger than the implementation
- [x] Launch Pro Edition: `gci` — fewer characters, more positioning
- [ ] **Space Reclamation™** — turn directory awareness into directory absence
- [ ] Evaluate whether scrolling counts as pagination
- [ ] Resist the urge to add a subscription
- [ ] Reach feature parity with the commands we already use

### Coming eventually: Space Reclamation™

*Don’t just discover your files. Discover life without them.*

| Proposed edition | Underlying command | Strategic outcome |
| :--- | :--- | :--- |
| Modern Experience | `Remove-Item` in PowerShell | Fewer items to observe |
| Legacy Enterprise | `del` in Windows CMD | Vintage file disappearance |
| Pro | `ri`, a PowerShell alias for `Remove-Item` | Shorter command. Same consequences. |

> **Destructive commands — roadmap joke only.** Unlike the listing commands, these commands can actually delete data and generally do not send it to the Recycle Bin. They are named here, not supplied as runnable deletion examples. No deletion feature, script or executable is included.

Product status: **marketing complete; implementation intentionally absent.**

## Frequently anticipated questions

**Does it use AI?**
No. The filenames were there the whole time.

**Can it tell me which folder is using all my disk space?**
Not with these commands alone. This is a directory listing, not a disk-usage analyser.

**Where is the download button?**
We achieved zero-download distribution by not distributing an application.

**Will this delete anything?**
The quick-start commands (`Get-ChildItem`, `dir` in CMD, and `gci`) only list items. Access errors may occur for folders you cannot read. The deletion commands named in the Space Reclamation roadmap are destructive and are not part of the quick start.

**Why is the documentation longer than the software?**
Enterprise readiness.

**Is the ™ serious?**
It is part of the joke. No trademark registration is claimed.

## Compatibility

The instructions target Windows with PowerShell or Command Prompt available. `Get-ChildItem` is also a PowerShell command on other platforms; `dir` here specifically means the Windows CMD built-in.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Improvements to the joke are welcome. Adding an actual storage engine would be a significant architectural regression.

## Credits

Made by **[Marco](https://github.com/marcovanthoog)**, for people who appreciate a beautifully over-engineered explanation of a very small thing.

The actual functionality is provided by Microsoft’s built-in [Get-ChildItem](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/get-childitem) and [dir](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/dir) commands. This project is not affiliated with Microsoft.

Original repository content is available under the [MIT License](LICENSE).

---

<div align="center">

**DISKVISION ULTRA™**
*Your files. Finally visible.*

<sub>No files were innovated upon during the making of this repository.</sub>

</div>
