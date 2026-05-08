# Fallen Empires Expanded

A content and overhaul mod for [Stellaris](https://store.steampowered.com/app/281990) that fleshes out the worlds, peoples, and ruins left behind by the galaxy's dormant precursors.

[![Status](https://img.shields.io/badge/Status-Work_in_progress-orange)](#status)
[![Discord](https://img.shields.io/badge/Discord-Modding_Den-5865F2?logo=discord&logoColor=white)](https://discord.gg/bHVez2C)

**Stellaris compatibility:** The mod works for 4.x, but is not ready for release.

---

## Status

> **This mod is unreleased and a work in progress.** Things may suddenly break, new things may be suddenly added. This is an Alpha version.

---

## Features

### Fallen Empire flavour
- New deposits and planet modifiers themed around the major Fallen Empire ethos paths
- New Precursor world variants: **Precursor World**, **Precursor Ring Segment**, and **Precursor Ecumenopolis**, each with their own modifiers
- Decayed Fallen Empire relic worlds
- A new **Ancient Holocron** relic, recovered from forerunner battlefields

### New empires and enclaves
- **Exodites** — pre-FTL societies of precursor descendants who deliberately chose simplicity over their forebears' decadence, while quietly retaining a few sophisticated technologies. Their warriors are deadlier than their archaic appearance suggests.
- **Exiles** — hostile, barbaric precursor cabals cast out from their home societies long ago. Raiding fleets like the *Cabal of Unyielding Valor* and *Cabal of the Merciless Tide* roam from a habitat called the *Tyrant's Throne*.
- A new FE themed **enclaves**

### Buildings, jobs, and civics
- **New buildings**
- **New jobs**
- **New civics**

### Galaxy generation and exploration
- Custom solar systems with their own setpieces
- New archaeological dig sites

### Events
- Dozens of new events
- New event chains

---

## Installation (from source)

Until a Workshop release exists, the mod is install-from-source only.

1. Clone or download this repository.
2. Copy the `content/` folder into your Stellaris `mod` directory under a folder name of your choice (e.g. `fallen_empires_expanded/`).
3. Create a matching `.mod` descriptor file in the `mod` directory pointing at that folder. A minimal example:

   ```
   name="Fallen Empires Expanded"
   path="mod/fallen_empires_expanded"
   supported_version="v3.14.*"
   ```

4. Enable **Fallen Empires Expanded** in the launcher's Mods tab and add it to your playset.

| OS      | Stellaris `mod` directory                                      |
|---------|----------------------------------------------------------------|
| Windows | `%USERPROFILE%\Documents\Paradox Interactive\Stellaris\mod\`   |
| macOS   | `~/Documents/Paradox Interactive/Stellaris/mod/`               |
| Linux   | `~/.local/share/Paradox Interactive/Stellaris/mod/`            |

> Starting a fresh save is strongly recommended — the mod adds galaxy generation content, custom systems, and country types that are spawned at game start.

---

## Compatibility

Compatibility has not yet been formally tested. The mod adds a large amount of new content (deposits, jobs, civics, country types, custom systems, events), and while there are no scripted-trigger overwrites in the current codebase, no guarantee is made about conflicts with other large overhaul mods.

If you find a conflict, please open an issue with the other mod's name, your load order, and steps to reproduce.

---

## Reporting bugs and contributing

This mod is in active development and feedback is welcome.

- **Bugs / suggestions:** open an [issue](../../issues) on this repository
- **Discussion:** join the [Modding Den Discord](https://discord.gg/bHVez2C)
- **Pull requests:** welcome — please describe what your change does and why. For larger content additions, open an issue first so the design can be discussed before you spend time on it.

When reporting a bug, please include:
- The exact commit hash you're running
- The Stellaris version
- Your full mod load order
- Steps to reproduce, an `error.log` excerpt if relevant, and a save file if possible

---

## License

[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0).

You are free to:

- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:

- **Attribution** — You must give appropriate credit, link to the license, and indicate if changes were made.
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

---

## Credits

- **Author:** Dunno
- Thanks to everyone in the Modding Den for ideas, feedback, and bug reports.
