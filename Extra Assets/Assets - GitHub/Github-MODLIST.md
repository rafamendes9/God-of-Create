# 📚 God of Create — Modlist

> Documented inventory of the components used by **God of Create** for Minecraft **1.21.1 + NeoForge 21.1.235**.

> **Important:** this file documents the functional components of the modpack. Mods, libraries, datapacks, resource packs, and shaderpacks are different types of components and are therefore listed in separate sections.

**---**

**## 📌 Document Status**

| Item                                           | Status                                                                                |
| ---------------------------------------------- | ------------------------------------------------------------------------------------- |
| Minecraft                                      | `1.21.1`                                                                              |
| Loader                                         | `NeoForge 21.1.235`                                                                   |
| Technological Base                             | **Create 6.x + Create Aeronautics**                                                   |
| Modpack                                        | **God of Create**                                                                     |
| Explicitly documented datapack                 | **WWOO**                                                                              |
| Other datapacks mentioned in the documentation | Incendium, Nullscape, and progression/civilization packs                              |
| Mentioned shaderpack                           | **Solas Shader**                                                                      |
| Physical `.jar` inventory                      | **Must be synchronized with the `mods/` folder before declaring the list exhaustive** |

**### Marker Reference**

* ✅ **Mod** — component loaded by NeoForge.
* 🧩 **Library / Dependency** — generally exists to support other mods.
* 🎨 **Client / Visual** — interface, rendering, or visual component.
* 🛠️ **Utility / QoL** — quality-of-life, information, management, or support component.
* 🌍 **Worldgen / Exploration** — world generation, structures, biomes, or exploration.
* 📦 **Datapack** — Minecraft datapack content; **not a mod**.
* 🌈 **Shaderpack** — shader package; **not a mod**.
* ⚠️ **Note** — name/family mentioned by the project that must be checked against the physical inventory before being considered an individual component.

**---**

**# 🧭 Pack Architecture**

God of Create can be divided into several major layers:

```text
                    ┌──────────────────────┐
                    │     GOD OF CREATE    │
                    └──────────┬───────────┘
                               │
        ┌──────────────────────┼──────────────────────┐
        │                      │                      │
        ▼                      ▼                      ▼
   ⚙️ CREATE               🪄 MAGIC              🌍 EXPLORATION
        │                      │                      │
        ▼                      ▼                      ▼
   🏭 Industry           Ars Nouveau             Worldgen
   📦 Logistics          Occultism               Structures
   🚂 Transportation     Neo Vitae               Dimensions
   ✈️ Aeronautics        Theurgy                 Mobs
        │                      │                      │
        └──────────────────────┼──────────────────────┘
                               │
                               ▼
                         🌌 SPACE / DIMENSIONS

                    ↘ 🏘️ MineColonies
                    ↘ ⚔️ Combat
                    ↘ 🎨 Visual / Performance
```

The systems are designed to coexist within the same long-term world rather than functioning as completely separate progression paths.

**---**

**# ⚙️ 1. Core — Create**

**## ✅ Create**

**Function:** core technological, mechanical, and industrial system of the modpack.

Create provides the foundation for:

* machines;
* power transmission;
* processing;
* automation;
* transportation;
* logistics;
* mechanisms;
* industrial construction;
* trains;
* contraptions;
* large-scale production.

**### Documented Version**

`Create 6.x`

The current project documentation references **Create 6.x**. For the exact installed version, check the `.jar` file in `mods/` or the distribution's control file.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/create

**---**

**# ✈️ 2. Aeronautics**

**## ✅ Create Aeronautics**

**Function:** Create expansion for vehicles and mobile physical structures.

It is one of the main pillars of the pack.

**### Main Concepts**

* ✈️ aircraft;
* 🎈 airships;
* 🚗 vehicles;
* ⚙️ physics-based contraptions;
* 🧱 mobile structures;
* 🧲 physics-based systems;
* 🛰️ aeronautical components;
* 🌐 integration with dynamic structures.

Create Aeronautics extends the Create ecosystem into vehicles and physics-based contraptions.

**### Version**

The project documentation does not specify the exact `.jar` version in the README.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/create-aeronautics

**---**

**## ✅ Sable**

**Function:** physics support system used by the Create Aeronautics ecosystem.

It is particularly relevant to:

* vehicle physics;
* mobile structures;
* dynamic behavior;
* simulation used by Aeronautics.

> ⚠️ **Sable is a dependency/infrastructure component associated with the Aeronautics ecosystem and should not be treated as a decorative Create addon.**

**---**

**# ⚙️ 3. Create — Addons and Expansions**

The current project documentation explicitly mentions the following addons/families.

> ⚠️ The names below represent components explicitly documented by the project. The physical `.jar` inventory must be used to determine the exact installed versions.

**## ⚡ Create: New Age**

Expansion focused on energy systems and electrical infrastructure.

**Usage in the pack:**

* energy;
* generation/transmission;
* technological integration.

**---**

**## 🍳 Create: Central Kitchen**

Expansion focused on food-related automation and processing.

**Usage in the pack:**

* food production;
* kitchen production lines;
* culinary automation.

**---**

**## ✨ Create: Enchantment Industry**

Expands Create with processes related to:

* experience;
* enchantments;
* automated production;
* integration with processing systems.

**---**

**## 🛢️ Create: Diesel Generators**

Adds a power-generation layer based on fuels and industrial infrastructure.

**Usage in the pack:**

* generators;
* fuel;
* electrical production;
* heavy industrial infrastructure.

**---**

**## 🧱 Create: Stuff Additions**

Additional content for the Create ecosystem.

> ⚠️ Confirm the exact entry in the `mods/` folder, as the README groups some addons under abbreviated names.

**---**

**## 🪟 Create Framed / Framed**

Expands modular construction and decoration.

**Usage in the pack:**

* framed blocks;
* detailed structures;
* industrial construction;
* decoration.

**---**

**## 🧩 Create Copycats / Copycats**

Expands modular construction based on Create components and appearances.

**Usage in the pack:**

* construction;
* cladding;
* block variants;
* architectural details.

**---**

**## 🌱 Create: Mechanical Botany**

Expands farming/botanical processes for integration with Create systems.

**Usage in the pack:**

* crop production;
* automation;
* factory integration.

**---**

**## 📐 Pattern Schematics**

Tools related to patterns and/or schematics for automated construction.

> ⚠️ The name should be checked against the installed file to distinguish projects with similar names.

**---**

**## 🏭 TFMG**

Industrial expansion focused on materials, machines, and heavier processes.

**Usage in the pack:**

* industry;
* materials;
* production;
* infrastructure.

**---**

**## 🔭 Create Optical**

Create ecosystem expansion related to optical and/or technical systems.

**---**

**## ⚡ Create Power Loader**

Chunk-loading tool associated with Create infrastructure.

**Usage in the pack:**

* chunk loading;
* automation that needs to remain active;
* remote bases/factories.

**---**

**## 📦 Create Mobile Packages**

Expands the package and logistics transportation system.

**---**

**## 🛤️ Hypertubes**

High-speed transportation/logistics system.

**Usage in the pack:**

* item transportation;
* logistics networks;
* automation.

**---**

**## ✈️ Ornithopter Glider**

Component related to transportation/aeronautics/gliding.

> ⚠️ Keep the description generic until the exact installed file and version are verified.

**---**

**# 🪄 4. Magic**

The pack uses several distinct magic systems.

**---**

**## ✅ Ars Nouveau**

**Function:** primary magic system based on spell creation.

**### Features**

* spell creation;
* custom spells;
* magical servants;
* tools;
* armor;
* automation;
* magical exploration.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/ars-nouveau

**---**

**## ✅ Ars Nouveau — Addons**

The README explicitly lists the following families:

**### Elemancy**

Magic content expansion.

**### Elemental**

Additional magical/elemental content.

**### Technica**

Integration between magic and technology.

**### Additions**

Additional Ars Nouveau content.

**### Creo**

Additional Ars Nouveau ecosystem integration/expansion.

**### Controle**

Component related to control/configuration of the magic system.

> ⚠️ The six names above appear explicitly in the README, but the names may correspond to individual projects, addons from the same family, or components that have changed names. Synchronize them with the actual `.jar` files.

**---**

**## ✅ Occultism**

**Function:** magic based on spirits, summoning, and supernatural automation.

**### Relevant Systems**

* summoning;
* spirits;
* rituals;
* storage;
* automation;
* magical progression.

**---**

**## ✅ Neo Vitae**

**Function:** blood-themed/ritualistic magic system.

**### Main Concepts**

* vital essence;
* altars;
* rituals;
* sacrifices;
* demons;
* entities;
* magical equipment;
* demonic dimension.

The mod is explicitly **datapack-driven**, but it remains a **mod**. Using datapacks internally does not make it a modpack datapack.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/neovitae

**---**

**## ✅ Forbidden Arcanus**

**Function:** fantasy/magic expansion featuring resources, items, equipment, and magical systems.

**---**

**## ✅ Theurgy**

**Function:** alchemy and transmutation.

**### Systems**

* alchemy;
* matter transmutation;
* artifacts;
* processes based on classical elements.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/theurgy

**---**

**# 🏘️ 5. MineColonies and Civilizations**

**## ✅ MineColonies**

**Function:** colony construction and management.

**### Systems**

* citizens;
* professions;
* construction;
* production;
* automation;
* defense;
* colony development;
* administration.

Integration with Create is one of the core concepts of God of Create.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/minecolonies

**---**

**## ✅ Structurize**

**Function:** library/infrastructure for MineColonies and construction systems.

> 🧩 This is infrastructure for the MineColonies ecosystem.

**---**

**## ✅ MultiPiston**

**Function:** library/infrastructure used by the MineColonies ecosystem for construction and movement systems.

**---**

**## ✅ BlockUI**

**Function:** interface library used by the MineColonies ecosystem.

**---**

**## ✅ Domum Ornamentum**

**Function:** large library/set of blocks and architectural variants, essential for construction and also used by the MineColonies ecosystem.

**### Highlights**

* block variants;
* walls;
* stairs;
* slabs;
* fences;
* decorative pieces.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/domum-ornamentum

**---**

**# 🏛️ 6. Structures and World Generation**

**---**

**## ✅ Larion**

**Function:** world and environment generation.

It is one of the components used by the project for world generation and exploration.

**---**

**## 🌊 Streams Reflowing**

**Function:** generation and behavior of watercourses.

The mod adds streams that follow terrain, flow toward lower areas, and integrate water flow into the landscape.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/streams-reflowing

**---**

**## ✅ Alex's Caves**

**Function:** underground exploration and special cave environments.

**### Highlights**

* unique biomes/caves;
* structures;
* mobs;
* resources;
* advanced underground exploration.

**---**

**## ✅ Deeper and Darker**

**Function:** Deep Dark expansion with new blocks, items, mobs, structures, and its own dimension.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/deeperdarker

**---**

**## ✅ Integrated Dungeons and Structures (IDAS)**

**Function:** replaces/expands world structures with detailed dungeons integrated with other mods.

It is part of the **Integrated Structures** family.

**---**

**## ✅ Integrated Stronghold**

**Function:** stronghold overhaul.

Adds a significantly more detailed structure and integrates content from mods such as:

* Create;
* Supplementaries;
* Quark;
* other structure components.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/integrated-stronghold

**---**

**## ✅ Integrated Villages**

**Function:** village overhaul.

Adds detailed structures and integration with other mods, including Create elements.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/integrated-villages

**---**

**## ✅ TerraBlender**

**Function:** world-generation/biome infrastructure used by other mods.

> 🧩 Normally a world-generation dependency rather than a content mod.

**---**

**# 🌌 7. Dimensions and Exploration**

**---**

**## ✅ The Aether**

**Function:** sky dimension with biomes, structures, creatures, resources, and its own progression.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/aether

**---**

**## ✅ Aether — Addons**

The README mentions several Aether addons.

> ⚠️ The addons should be listed individually once the `.jar` files are synchronized with the physical inventory.

**---**

**## ✅ Northstar / North Star Redux**

**Function:** space exploration layer.

The project uses the system for:

* rockets;
* space;
* exploration;
* stations;
* environments beyond the surface.

> ⚠️ Confirm the exact installed project name. The pack documentation currently uses both **Northstar** and **North Star Redux**.

**---**

**# 🌍 8. Nether and End — Datapacks**

> 🚨 **This section is deliberately separated from “Mods”.**

**---**

**## 📦 WWOO**

**Type:** Datapack

**Function:** world generation / immersive environments.

**### Important**

**WWOO is not a mod.**

It must be counted and installed as a datapack, not as a file in the `mods` category.

**---**

**## 📦 Incendium**

**Type:** Datapack

**Function:** Nether overhaul.

Adds/changes:

* biomes;
* structures;
* environments;
* exploration;
* Nether content.

**---**

**## 📦 Nullscape**

**Type:** Datapack

**Function:** End overhaul.

Adds:

* new environments;
* terrain/worldgen;
* exploration;
* End landscapes.

**---**

**## 📦 Progression / Civilization Datapacks**

The pack documentation also mentions datapacks intended for:

* progression;
* MineColonies;
* civilizations;
* colony styles;
* nations/cultures.

> ⚠️ Each datapack should be listed individually in the final version of this documentation.

**---**

**# 🧩 9. Paxi**

**## ✅ Paxi**

**Type:** Utility mod for global datapacks/resource packs.

**Function:** automatically loads global content without requiring manual installation in every world.

The mod creates/uses a `paxi` folder for global content.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/paxi

**### Important**

Paxi is a **mod**.

The files it loads can be **datapacks or resource packs**.

**---**

**# 🐉 10. Mobs, Adventure and Combat**

**---**

**## ✅ Cataclysm**

**Function:** bosses, structures, and high-difficulty combat.

Used in the pack as one of the major adventure/endgame components.

**---**

**## ✅ Born in Chaos**

**Function:** new enemies, threats, and combat content.

**---**

**## ✅ Mowzie's Mobs**

**Function:** new mobs and combat encounters focused on behavior and bosses.

**---**

**## ✅ Alex's Mobs**

**Function:** large expansion of fauna and creatures.

**---**

**## ✅ Sea Life**

**Function:** aquatic environment/marine life expansion.

The project has a NeoForge 1.21.1 version.

**---**

**# 👩‍🚀 11. Touhou Little Maid**

**## ✅ Touhou Little Maid**

**Function:** adds maids as companions.

**### Features**

* maids;
* models;
* companionship;
* behaviors;
* interaction;
* equipment and task support.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/touhou-little-maid

**---**

**## ✅ Maid Dimension**

**Function:** personal dimension associated with the Touhou Little Maid ecosystem.

Can be used as:

* refuge;
* storage;
* dedicated space;
* customized environment.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/maid-dimension

**---**

**# 🔫 12. TACZ**

**## ✅ Timeless and Classics Zero (TACZ)**

**Function:** firearms and tactical combat.

The system adds a combat layer distinct from vanilla Minecraft.

**### In the God of Create Context**

Integration with Touhou Little Maid is used as part of the concept of companions capable of participating in adventures.

> ⚠️ “TACZ + addons and skins” is a family; addons should be listed individually in the physical inventory.

**---**

**# 🐕 13. Companions**

**## ✅ Doggy Talents Next**

**Function:** dog/wolf expansion.

Can add:

* attributes;
* abilities;
* progression;
* companion utility;
* customization.

**---**

**# ⚔️ 14. Other Adventure Content**

**## ✅ Protection Pixel**

**Function:** combat/protection content.

> ⚠️ Keep the description conservative until the exact version and `.jar` are verified.

**---**

**# 🎨 15. Interface and Information**

**---**

**## ✅ Just Enough Items (JEI)**

**Function:** recipes, uses, and item/block lookup.

One of the most important tools for a high-complexity modpack.

**### Usage**

* view recipes;
* find uses;
* inspect components;
* search hundreds of items.

**---**

**## ✅ Just Enough Resources (JER)**

**Function:** information about resource generation and acquisition.

**---**

**## ✅ Just Enough Professions (JEP)**

**Function:** information about villager professions and trades.

**---**

**## ✅ Just Enough Breeding (JEB)**

**Function:** information related to animal breeding.

**---**

**## ✅ Jade**

**Function:** contextual information HUD.

Can display:

* observed block;
* entity;
* additional information;
* useful details during construction and exploration.

**---**

**## ✅ Xaero's Minimap**

**Function:** minimap.

**---**

**## ✅ Xaero's World Map**

**Function:** world map.

**---**

**## ✅ FancyMenu**

**Function:** menu and screen customization.

**---**

**## ✅ Not Enough Animations**

**Function:** adds/expands player action animations.

**---**

**## ✅ Entity Model Features**

**Function:** advanced visual features for entity models.

**---**

**## ✅ Entity Texture Features**

**Function:** advanced entity texture features.

**---**

**## ✅ Continuity**

**Function:** visual continuity and connected textures when supported.

**---**

**## ✅ Drippy Loading Screen**

**Function:** loading screen customization.

**---**

**# 🧱 16. Building and Decoration**

**---**

**## ✅ Supplementaries**

**Function:** large collection of Vanilla+ building, decoration, automation, and utility elements.

Examples:

* jars;
* signposts;
* faucets;
* weather vanes;
* light sources;
* decorative elements;
* utility components.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/supplementaries

**---**

**## ✅ Handcrafted**

**Function:** furniture and decoration.

**---**

**## ✅ Blueprint**

**Type:** Library

**Function:** shared infrastructure used by Team Abnormals mods.

Should not be treated as primary gameplay content.

**### Source**

* https://modrinth.com/mod/blueprint

**---**

**## ✅ Gallery**

**Function:** visual building/decoration component.

> ⚠️ Confirm the exact installed project.

**---**

**## ✅ Amendments**

**Function:** Vanilla+ improvements and decoration/interaction adjustments.

**---**

**## ✅ Structure Essentials**

**Function:** structure-related support/control.

Within the pack, it should be considered part of the worldgen/structure layer.

**---**

**## ✅ Lithostitched**

**Type:** Library

**Function:** infrastructure for worldgen and structure integration/management.

**---**

**# 🏦 17. Trading, Logistics and Economy**

**---**

**## ✅ Trading Post**

**Function:** villager trading management/interaction.

**---**

**## ✅ Create Trading Floor**

**Function:** integration of trading with the Create ecosystem.

**---**

**## ✅ Stock Bridge**

**Function:** inventory/logistics infrastructure.

**---**

**## ✅ Package Couriers**

**Function:** package transportation.

**---**

**## ✅ Mobile Packages**

**Function:** package movement and logistics.

**---**

**# 👥 18. Claims, Chunks and Progression**

**---**

**## ✅ Open Parties and Claims**

**Function:**

* claims;
* area protection;
* groups/parties;
* territorial management.

> ⚠️ The current README documents a case where **Open Parties and Claims claims can interfere with Create Aeronautics entities/SubLevels**. This should be treated as a known compatibility issue and tested before recommending claims on aeronautical structures.

**---**

**## ✅ Create Power Loader**

**Function:** chunk loading associated with Create systems.

**---**

**## ✅ FTB Quests**

**Function:** quest/progression system.

Can be used for:

* guides;
* progression;
* objectives;
* milestones;
* content integration.

**---**

**# 🚀 19. Performance and Optimization**

**---**

**## ✅ Sodium**

**Function:** optimized rendering.

One of the central components of the graphical configuration.

**---**

**## ✅ Lithium**

**Function:** optimization of game logic/ticks and internal behavior.

**---**

**## ✅ ImmediatelyFast**

**Function:** optimization of rendering and graphical operations.

**---**

**## ✅ FerriteCore**

**Function:** reduces memory usage in certain internal Minecraft/mod structures.

**---**

**## ✅ ModernFix**

**Function:** broad optimization of memory, loading, and performance.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/modernfix

**---**

**## ✅ Alternate Current**

**Function:** redstone optimization.

**---**

**## ✅ Clumps**

**Function:** groups experience orbs to reduce entity count.

**---**

**## ✅ Neruina**

**Function:** prevention/control of certain ticking and problematic entity issues.

**---**

**## ✅ AllTheLeaks**

**Function:** diagnosis/mitigation of memory leak-related problems.

**---**

**## ✅ Chunk Sending**

**Function:** optimize chunk transmission.

**### Source**

* https://www.curseforge.com/minecraft/mc-mods/chunk-sending-forge-fabric

**---**

**## ✅ Smooth Chunk**

**Function:** smooths certain chunk/loading operations.

> ⚠️ Confirm the exact installed version/project.

**---**

**## ✅ Entity Culling**

**Function:** prevents rendering of entities that cannot be seen by the player.

**---**

**## ✅ More Culling**

**Function:** increases the number of objects discarded from the rendering process when they are not visually required.

**---**

**## ✅ Cull Leaves**

**Function:** leaf-specific optimization.

**---**

**## ✅ ScalableLux**

**Function:** lighting-system optimization.

**---**

**# 🌄 20. Distant Horizons**

**## ✅ Distant Horizons**

**Function:** LOD rendering for extremely large distances.

**### Why it matters in God of Create**

The pack encourages:

* large cities;
* factories;
* railways;
* bridges;
* airports;
* large structures;
* large-scale exploration.

This makes long-distance rendering particularly relevant.

**### Performance Note**

LOD generation can cause significant system load, especially during initial exploration.

The project therefore recommends managing:

* distant generation;
* LOD distance;
* CPU load;
* quality;
* shaders.

**---**

**# 🌈 21. Shaders**

**## 🌈 Solas Shader**

**Type:** Shaderpack

**Function:** improves lighting, atmosphere, shadows, water, and overall appearance.

> 🚨 Solas is a **shaderpack**, not a mod.

In God of Create, shader usage is separate from:

* Sodium;
* Iris;
* Distant Horizons.

**---**

**## ✅ Iris**

**Function:** shaderpack loading.

Iris is the component that enables shaderpacks in the supported environment.

**---**

**# 🧩 22. Infrastructure / Libraries**

This section documents components that primarily exist to support other mods.

| Component        | Role                                     |
| ---------------- | ---------------------------------------- |
| Sable            | Aeronautics physics/infrastructure       |
| Blueprint        | Team Abnormals library                   |
| TerraBlender     | Worldgen/biome API                       |
| Lithostitched    | Worldgen/structures                      |
| Structurize      | MineColonies infrastructure              |
| MultiPiston      | MineColonies infrastructure              |
| BlockUI          | MineColonies UI                          |
| Domum Ornamentum | Architectural blocks/infrastructure      |
| Integrated API   | Integrated Structures infrastructure     |
| Paxi             | Global datapack/resource pack management |

> ⚠️ The physical `mods/` inventory should be used to confirm which libraries are present and which are transitive dependencies.

**---**

**# 📦 23. Datapacks — Inventory**

| Datapack                              | Function                          | Type        |
| ------------------------------------- | --------------------------------- | ----------- |
| **WWOO**                              | Worldgen / immersive environments | 📦 Datapack |
| **Incendium**                         | Nether overhaul                   | 📦 Datapack |
| **Nullscape**                         | End overhaul                      | 📦 Datapack |
| **Create + MineColonies Progression** | Progression/quests/advancement    | 📦 Datapack |
| **Civilizations / Nations**           | Colony themes/styles              | 📦 Datapack |

**### Fundamental Rule**

```text
mods/*.jar        → MODS

paxi/*.zip        → DATAPACKS / RESOURCE PACKS

saves/.../datapacks
                   → DATAPACKS

shaderpacks/*     → SHADERS

resourcepacks/*   → RESOURCE PACKS
```

**Do not count WWOO, Incendium, or Nullscape as mods.**

**---**

**# 🖼️ 24. Resource Packs**

The project includes resource packs, including content distributed through the external assets folder.

These contents may modify:

* textures;
* models;
* sounds;
* block appearance;
* entity appearance;
* screens;
* visual elements.

> ⚠️ Individual names should be registered here after synchronization with `resourcepacks/` and `Extra Assets`.

**---**

**# 📁 25. Extra Assets**

The repository contains an:

```text
Extra Assets/
```

folder.

Its purpose is to provide content that is not stored directly in the main repository due to size and/or distribution limitations.

These items may include:

* mods;
* datapacks;
* shaders;
* resource packs;
* other required files.

**### Rule**

An item located in `Extra Assets` **must not automatically be classified as a mod**.

The classification must follow the actual component type.

**---**

**# 🔗 26. Official Sources**

The following pages can be used to identify projects and check compatible versions:

* Create — https://www.curseforge.com/minecraft/mc-mods/create
* Create Aeronautics — https://www.curseforge.com/minecraft/mc-mods/create-aeronautics
* Ars Nouveau — https://www.curseforge.com/minecraft/mc-mods/ars-nouveau
* Neo Vitae — https://www.curseforge.com/minecraft/mc-mods/neovitae
* Theurgy — https://www.curseforge.com/minecraft/mc-mods/theurgy
* Touhou Little Maid — https://www.curseforge.com/minecraft/mc-mods/touhou-little-maid
* Maid Dimension — https://www.curseforge.com/minecraft/mc-mods/maid-dimension
* MineColonies — https://www.curseforge.com/minecraft/mc-mods/minecolonies
* Supplementaries — https://www.curseforge.com/minecraft/mc-mods/supplementaries
* Deeper and Darker — https://www.curseforge.com/minecraft/mc-mods/deeperdarker
* Integrated Stronghold — https://www.curseforge.com/minecraft/mc-mods/integrated-stronghold
* Integrated Villages — https://www.curseforge.com/minecraft/mc-mods/integrated-villages
* Aether — https://www.curseforge.com/minecraft/mc-mods/aether
* Blueprint — https://modrinth.com/mod/blueprint
* Paxi — https://www.curseforge.com/minecraft/mc-mods/paxi
* ModernFix — https://www.curseforge.com/minecraft/mc-mods/modernfix
* Chunk Sending — https://www.curseforge.com/minecraft/mc-mods/chunk-sending-forge-fabric
* Streams Reflowing — https://www.curseforge.com/minecraft/mc-mods/streams-reflowing
* Domum Ornamentum — https://www.curseforge.com/minecraft/mc-mods/domum-ornamentum
* Sea Life — https://www.curseforge.com/minecraft/mc-mods/sea-life

**---**

**# 🧪 27. Checklist for a 100% Accurate Inventory**

Before considering this file the **official and exhaustive MODLIST**, synchronize:

```text
God of Create - Modpack/

├── mods/
├── config/
├── defaultconfigs/
├── paxi/
├── resourcepacks/
└── shaderpacks/

Extra Assets/
```

Then, for each component:

* [ ] project name;
* [ ] `.jar`/file name;
* [ ] version;
* [ ] loader;
* [ ] category;
* [ ] client/server/both;
* [ ] required/optional;
* [ ] dependencies;
* [ ] source platform;
* [ ] compatibility notes.

**---**

**# 📊 28. Recommended Final Table Structure**

Once the physical inventory is synchronized, the master table should use:

| Name               | Version | Type     | Category           | Side   | Required | Dependencies | Source     | Notes         |
| ------------------ | ------- | -------- | ------------------ | ------ | -------- | ------------ | ---------- | ------------- |
| Create             | 6.0.10  | Mod      | Automation         | C/S    | ✅        | —            | CurseForge | Core          |
| Create Aeronautics | 1.3.x   | Mod      | Aeronautics        | C/S    | ✅        | Sable        | CurseForge | Core          |
| Distant Horizons   | x.x.x   | Mod      | Performance/Visual | C/S    | ✅*       | —            | —          | LOD           |
| WWOO               | x.x     | Datapack | Worldgen           | C/S    | ✅*       | —            | —          | **Not a mod** |
| Solas              | x.x     | Shader   | Visual             | Client | ❌        | Iris         | —          | Shaderpack    |

`*` depends on the official pack profile/distribution.

**---**

**# ⚠️ 29. Documented Compatibility Issues**

**## Create Aeronautics × Open Parties and Claims**

The project README documents that claims from Open Parties and Claims can interfere with Aeronautics entities/SubLevels.

**### Documented Recommendation**

If you encounter:

* entities that do not break;
* SubLevels that stop updating;
* abnormal behavior in aeronautical structures;

test the affected area without claims.

**---**

**## Chipped × Rechiseled**

The project reports possible texture loading delays in inventory systems such as JEI, mainly due to the large amount of visual content.

**---**

**## Distant Horizons × World Generation**

LOD generation in heavily modified worlds can create significant initial system load.

The project recommends controlling:

* distance;
* quality;
* CPU load;
* distant generation.

**---**

**# 🔍 30. Completeness Note**

This document is intentionally **conservative**.

The current public God of Create README contains expressions such as:

* `+ addons`;
* `more...`;
* `dozens of other addons`;
* `etc.`;

These expressions are not sufficient to produce a physical, auditable list of every `.jar` using the README alone.

Therefore:

> **Do not consider this file the definitive mod count until the `mods/` inventory has been reconciled with this documentation.**

This file serves as the **official documentation structure** and can be used as the basis for the complete physical inventory.

**---**
