# Cthulhu Invictus: Britannia & Beyond — Foundry VTT Module

An expansion module for **Cthulhu Invictus** set in the Roman province of **Britannia**, the barbarian lands of **Caledonia**, and **Hibernia** during the reign of Antoninus Pius (145 A.D.).

Based on *Britannia & Beyond* by Golden Goblin Press.

## Requirements

- **Foundry VTT** v13+
- **Call of Cthulhu 7th Edition** system (`CoC7`) v0.10.0+
- **Cthulhu Invictus** module (`coc7-cthulhu-invictus`) v1.0.0+ — *required dependency*

## Features

This module adds content only — no new mechanical systems. All optional rules from Module 1 work seamlessly with Britannia content.

### Bestiary (28 creatures)

**Wildlife of Britannia (14)**
Aurochs, Brown Bear, Caledonian Wolf, Irish Elk, Wild Boar, Lynx, Badger, Celtic Wildcat, Roe Deer, Red Deer, White-tailed Eagle, and three breeds of British dogs (Hunting, Guard, War).

**Folklore Monsters (8)**
Agassian, Baobhan Sith (vampire), Changeling, Hag (Cailech), Kelpie, Leannan Sidhe, Llamhigyn Y Dwr (water leaper), Selkie — all drawn from Celtic and British folklore with full CoC7 stat blocks.

**Mythos Entities (6)**
Byatis (the Serpent-Bearded), Eihort (Beast of the Labyrinth), Gla'aki and Servants, Y'golonac, Yegg-ha (Scourge of the Legions), Aphoom Zhah — Great Old Ones and entities with British Isles connections.

### Lore Journals (10 entries)

Comprehensive setting reference covering the history, geography, people, religion, and supernatural landscape of Roman Britannia, organized by chapter from the sourcebook:

- The Shadow War of Britannia (overview)
- A History of Britannia
- Life in Roman Britannia
- Geography, Economy & Trade
- The People of Britannia (Roman settlers, Celtic tribes, Northern tribes)
- A Tour of the Province (major cities, Hadrian's Wall, Valentia, the frontier)
- Religion & the Druids
- The Mythos in Britannia
- Caledonia, the Land of the Picts
- Hibernia, the Land of Winter

### Patrons & Organizations (3)

- **Centuria VII Munerum Extraordinariorum** — Military unit tasked with supernatural threats
- **The Iron Society** — Druidic resistance network opposing Mythos corruption
- **Praefectura Civilis VII** — Civilian administration dealing with unexplained events

## Third-Party IP Advisory

This module includes creatures and elements by Ramsey Campbell (Byatis, Eihort, Gla'aki, Y'golonac), Brian Lumley (Yegg-ha), the Clark Ashton Smith estate (Tsathoggua), the Lin Carter estate (Aphoom Zhah), and Robert E. Howard's estate via Cabinet Licensing LLC (Valusia). Confirm explicitly with Golden Goblin Press that your digital module license covers these third-party elements before any public release.

### Adventure Scenarios (2)

Two complete adventures packaged as Foundry Adventure documents with NPCs, creatures, handout props, items, scene-by-scene Keeper notes, and rollable tables.

**The Long Dark** — 13 NPCs, 2 creature types, 8 scenes, 3 props, 1 rollable table. An investigation in rural Britannia involving ancient underground horrors and a Celtic festival gone wrong.

**A Mortal Harvest** — 12 NPCs, 2 creature types (including Gla'aki), 9 scenes, 2 artifacts, 1 handout. A journey from Viroconium into the Otherworld to confront a Great Old One threatening the harvest.

*Note: Map scene images require asset rights confirmation from Golden Goblin Press. Placeholder fog-of-war scenes with text descriptions are used until permission is granted.*

## Installation

1. Install the base **coc7-cthulhu-invictus** module first
2. Download or clone this repository into `Data/modules/coc7-britannia-beyond`
3. Activate both modules in your CoC7 world

## Project Structure

```
coc7-britannia-beyond/
├── module.json                              # Manifest (depends on coc7-cthulhu-invictus)
├── lang/en.json                             # English localization
├── styles/britannia.css                     # Supplementary styles
├── packs/
│   ├── bestiary/_source/                    # 28 creature Actors
│   ├── journal/_source/                     # 10 lore JournalEntries
│   ├── patrons-and-organizations/_source/   # 3 organization JournalEntries
│   ├── the-long-dark/_source/               # 21 adventure documents
│   └── a-mortal-harvest/_source/            # 18 adventure documents
└── .gitignore
```

## Credits

- **Setting**: *Britannia & Beyond* by Oscar Rios, published by Golden Goblin Press
- **System**: Call of Cthulhu 7th Edition for Foundry VTT by the Miskatonic Investigative Society
- **Module Development**: Built with assistance from Claude (Anthropic)

## License

Fan-made digital implementation for personal use. All intellectual property belongs to respective rights holders. Confirm licensing before public distribution.
