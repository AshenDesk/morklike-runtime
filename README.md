# MÖRK BORG — Interactive Solo Edition v1.0.1

> *"A doom metal album of a game."*
> A web-based, offline-capable solo RPG adaptation of MÖRK BORG.

---

## Overview

This is an unofficial, fan-made interactive adaptation of [MÖRK BORG](https://morkborg.com/) — a rules-light, art-punk tabletop RPG published by **Ockult Örtmästare Games** and **Stockholm Kartell**. The goal is to faithfully bring the game's mechanics, atmosphere, and lethality to a single-file HTML experience playable on any device, with no internet required.

The initial campaign module is **Rotblack Sludge**, a dungeon crawl included in the MÖRK BORG core book. Future expansions may include additional scenarios, classes, and campaign modules.

---

## Features

- **Single-file HTML** — no installation, no server, no dependencies. Open and play.
- **Offline-capable** — works fully without internet access.
- **Mobile-first UI** — responsive layout designed for phones and tablets, with a desktop view.
- **RAW-faithful mechanics** — dice rolls, DR tests, Broken table, Calendar of Nechrubel, and combat follow the MÖRK BORG rules as closely as possible for a solo digital experience.
- **Solo play** — designed for single-player without a GM, with automated enemy behaviour and narrative events.
- **Two visual themes** — *Forge* (dark, atmospheric) and *RAW* (high-contrast art-punk, closer to the printed book's aesthetic).
- **Persistent state** — game state saved in `localStorage`; theme preference persists across sessions.

---

## Current Campaign: Rotblack Sludge

The player descends into a cursed dungeon beneath a dying world. Fifteen interconnected rooms, each with handcrafted interactions, enemies, traps, secrets, and multiple resolution paths.

**Implemented systems:**

- Six playable classes (Gutterborn Scum, Heretical Priest, Fanged Deserter, Occult Herbmaster, Sacrilegious Songbird, Pale One) — each with unique starting gear and class ability
- Combat: attack/defend rolls, critical hits, fumbles, enemy morale, armor degradation
- Broken table (d4): Unconscious, Broken Limb, Haemorrhage, Death
- Calendar of Nechrubel — time advances with actions, triggering misery rolls
- Inventory, encumbrance, silver economy, trading
- Ranged weapons with bolt tracking
- Status effects: bleeding, infection, burning, unconscious, buffs/debuffs
- Guard Room with sneak, bribe, and combat paths — guards persist and pursue
- Cells with individual prisoners (A/B/C), negotiation, lockpicking, chaos strategies
- Fletcher the Cannibal Warlock — pursuit across Forge, Debris, Statue, and Pump rooms
- The Gutworm — emergent encounters tied to noise, bleeding, and erratic movement
- Chain Room north door — examination, forced entry, iron hook mechanic
- Tunnel with heavy armor restriction and greenhouse crawl
- Flee system with adjacent-room choice

---

## Updates - ver 1.0.1

- 08/05/2026 - Occult Herbmaster: Alternative move in Tunnels when using Spider-Owl Soup (after falling from a trap): [CLIMB BACK UP THE PIT SHAFT (SPIDER-OWL SOUP)]

---

## Planned

- Additional campaign modules
- More class abilities and starting scenarios
- Extended enemy roster
- Save/load slots
- Expanded loot and item interactions

---

## Legal & License

### This Project

The code and original content in this repository are released under the **MIT License** — see [`LICENSE`](LICENSE) for details.

You are free to fork, modify, and redistribute this project, provided the attribution and license notice is retained and the conditions below regarding third-party IP are respected.

### MÖRK BORG IP

**MÖRK BORG** is © Ockult Örtmästare Games & Stockholm Kartell 2019. This project is **not affiliated with, endorsed by, or officially connected to** Ockult Örtmästare Games or Stockholm Kartell in any way.

This project is built on the **MÖRK BORG System Reference Document (SRD)**, which is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). The SRD covers core mechanics (attributes, DR tests, combat, the Broken table, the Calendar of Nechrubel, and class archetypes).

**Rotblack Sludge** is a dungeon module from the MÖRK BORG core book. Its content (room descriptions, enemy statistics, specific narrative text) is reproduced and adapted here for non-commercial fan use only, under the terms of MÖRK BORG's third-party licence:

> *MÖRK BORG is a product of Ockult Örtmästare Games & Stockholm Kartell,*
> *published under the MÖRK BORG Third Party Licence.*
> *[https://morkborg.com/license/](https://morkborg.com/license/)*

This project does **not** reproduce the full text, artwork, or layout of the MÖRK BORG core book. It is a free, non-commercial fan work intended to promote the original game.

**If you enjoy this adaptation, please buy the original:**
- [MÖRK BORG PDF + Print](https://morkborg.com/content/) via Free League Publishing
- [itch.io](https://freeleaguepublishing.itch.io/mork-borg)

---

## Running the Project

No build step required. Clone or download the repository and open `index.html` in any modern browser.

```bash
git clone https://github.com/Loboguar4/morklike-runtime
cd morklike-runtime
open index.html   # macOS
# or double-click index.html on Windows/Linux
```

Room illustration images (if any) should be placed in an `images/` folder alongside `index.html`. The game runs without them — missing images fail silently.

---

## Contributing

Issues and pull requests are welcome. If you're adding content derived from MÖRK BORG, please ensure it falls within the scope of the SRD (CC BY 4.0) or the MÖRK BORG Third Party Licence.

For mechanical bugs, please include the room, action taken, and the exact log output.

---

## Acknowledgements

- **Johan Nohr & Magnus Pålsson** — creators of MÖRK BORG
- **Ockult Örtmästare Games & Stockholm Kartell** — publishers
- The MÖRK BORG community and third-party ecosystem for keeping the game alive

---

*The world is dying. You are complicit. Play anyway.*
