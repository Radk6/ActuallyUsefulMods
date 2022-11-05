# Performance Mods

A list of performance-enhancing mods for 1.12.x Forge/Fabric versions.

[![Home](https://i.imgur.com/zGuelkW.png)](/README.md)

## Forge 1.12.X

| Name | Known Incompatibilities | Description | Author | Performance Improvement | [Label](/README.md/#labels) |
| --- | :---: | :---: | :---: | :---: | :---: |
| [AE2 Unofficial Extended Life](https://www.curseforge.com/minecraft/mc-mods/ae2-extended-life) | Applied Energistics 2 | This is a Fork of [Applied Energistcs 2](https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2) since 1.12.2 in no longer supported, This version of AE2 comes with many bugfixes and performance improvments | PrototypeTrousers | Both | None |
| [AI Improvements](https://www.curseforge.com/minecraft/mc-mods/ai-improvements) | None | Simplified AI modification mod focused on performance and low-level modifications to AIs in the game | QueenOfMissiles | Server | None |
| [Better Biome Blend](https://www.curseforge.com/minecraft/mc-mods/better-biome-blend) | None | Better Biome Blend is a mod  which accelerates the biome color blending algorithm. | FionaTheMortal | Client | None |
| [BetterFPS](https://www.curseforge.com/minecraft/mc-mods/betterfps) | None | BetterFps is a Minecraft mod that add a few performance improvements, trying to be compatible with other mods. | Guichaguri | Both | None |
| [Born In a Barn](https://www.curseforge.com/minecraft/mc-mods/born-in-a-barn) | Unknown | Fixes a Minecraft bug where Village doors keep chunks loaded. | Speiger | Server | None |
| [Chunk-Pregenerator](https://www.curseforge.com/minecraft/mc-mods/chunkpregenerator) | Unknown | Chunk Pregenerator is a tool that allows you to generate your World more efficiently, by Preemptively generating the chunks. It is a Server-side tool that has some optional client features if wanted. | Speiger | Both | Configuration Needed (7) |
| [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps) | None | Clumps groups XP orbs together into a single entity to reduce lag when there are many in a small area | jaredlll08 | Both | None |
| [Entity Culling](https://www.curseforge.com/minecraft/mc-mods/entity-culling) | Pixelmon, Sync | Entity Culling is a small client-side performance core mod which improves the rendering of entities and tile entities. | meldexun | Client | None |
| [FastFurnace](https://www.curseforge.com/minecraft/mc-mods/fastfurnace) | None | Similar to FastWorkbench, it caches the last recipe used, and checks this recipe first before re-scanning the entire registry. | Shadows_of_Fire | Server (Must be installed in client as well) | None |
| [FastWorkbench](https://www.curseforge.com/minecraft/mc-mods/fastworkbench) | None | This is a mod aimed at improving performance of all crafting-related functions. | Shadows_of_Fire | Server (Must be installed in client as well) | None |
| [FoamFix](https://www.curseforge.com/minecraft/mc-mods/foamfix-optimization-mod) | None | FoamFix is a mod designed to optimize post-1.7.10 modded Minecraft using simple, targeted optimizations | asiekierka | Both | None |
| [Get It Together, Drops!](https://www.curseforge.com/minecraft/mc-mods/get-it-together-drops) | None | This mod adds two configuration options to control how dropped items combine on the ground. This can significantly improve performance in areas with lots of dropped items | bl4ckscor3 | Server | None |
| [Had Enough Items](https://www.curseforge.com/minecraft/mc-mods/had-enough-items) | Unknown | A fork of Just Enough Items with memory and performance optimizations | CleanroomMC, Rongmario | Client | None |
| [燐/Hesperus](https://www.curseforge.com/minecraft/mc-mods/hesperus) | Mods using outdated mixin versions[¹](/README.md#-should-work-if-mixin-0-7-0-8-compatibility-is-applied)  | Continuation of Phosphor for 1.12.2, with improved compatibility | kappa_maintainer | Both | None |
| [Let Me Despawn](https://www.curseforge.com/minecraft/mc-mods/let-me-despawn) | Unknown | Helps with lag caused by accidental persistent mobs. | frikinjay1 | Server | Reverse features (7) |
| [Multithreaded Noise](https://www.curseforge.com/minecraft/mc-mods/multithreaded-noise) | Unknown | This mod makes overworld terrain generate faster by replacing the three 3D noise generators in the overworld with multithreaded versions. | bloodnbonesgaming | Server | Alpha (1) |
| [NormalASM](https://www.curseforge.com/minecraft/mc-mods/normalasm) | TexFix, VanillaFix | Optimize RAM usage. | Rongmario, mirrorcult | Both | None |
| [Nothirium](https://www.curseforge.com/minecraft/mc-mods/nothirium) | Unknown | Nothirium is a client-side only mod that changes Minecraft's chunk rendering engine to use modern OpenGL which greatly increases performance. This mod is similar to Sodium but this is not a port of Sodium. | meldexun | Client | None |
| [Particle Culling](https://www.curseforge.com/minecraft/mc-mods/particle-culling) | None | This mod is a client-side performance enhancing mod, which stops particles that are outside the player's view from rendering | bl4ckscor3 | Client | None |
| [Performant](https://www.curseforge.com/minecraft/mc-mods/performant) | Bewitchment | Lightweight mod project which hugely improves performance and blocklag. | someaddon | Server | Incompatible (2) |
| [PortalSuperCache](https://github.com/LucunJi/PortalSuperCacheForge112/releases) | Unknown | When using this mod, your game will search portal blocks at a high speed on teleport. | LucunJi | Server | Alpha (?) |
| [Potion Core](https://www.curseforge.com/minecraft/mc-mods/potion-core) | Unknown | Fixes stuttering when breaking/placing blocks when used in conjunction with OptiFine | Tmtrvlr | Both | None |
| [Stackie](https://www.curseforge.com/minecraft/mc-mods/stackie) | Unknown | This mod increases stack sizes of experience and items | Lunatrius | Server | None |
| [Surge](https://www.curseforge.com/minecraft/mc-mods/surge) | Mods using outdated mixin versions[¹](/README.md#-should-work-if-mixin-0-7-0-8-compatibility-is-applied) | Surge is an open source mod which aims to improve the load time and performance of the game. | DarkhaxDev | Both | None |
| [TexFix](https://www.curseforge.com/minecraft/mc-mods/texfix) | **FoamFix-Anarchy**, MCPatcher | TexFix optimizes the loading of textures of other mods | Speiger | Client | None |
| [Tick Dynamic](https://www.curseforge.com/minecraft/mc-mods/tick-dynamic) | Unknown | Attempts to keep the server at 20tps by dynamically limiting the amount of entities and tile-entities that update per tick | The_Fireplace / wildex999 | Server | None |
| [Tinkers OreDict Cache](https://www.curseforge.com/minecraft/mc-mods/tinkers-oredict-cache) | Unknown | This mod caches Tinkers Construct melting recipes to speed up game loading time | youyihj | Both | None |
| [Tiquality](https://www.curseforge.com/minecraft/mc-mods/tiquality) | Unknown | Limiting a player's tick time in the world to evenly distribute time. | Terminator_NL | Server | None |
| [Unloader](https://www.curseforge.com/minecraft/mc-mods/unloader) | Unknown | Checks for unused dimensions every 30 seconds (600 ticks) to unload by default | Unnoen | Both | None |
| [VanillaFix](https://www.curseforge.com/minecraft/mc-mods/vanillafix) | Mods using outdated mixin versions[¹](https://github.com/NordicGamerFE/usefulmods/tree/main#-should-work-if-mixin-0-7-0-8-compatibility-is-applied) | VanillaFix is a mod that improves performance and fixes bugs and annoyances in vanilla Minecraft | Runemoro (Dimensional Development) | Both | None |

## Legacy Fabric 1.12.X

| Name | Known Incompatibilities | Description | Author | Performance Improvement | [Label](/README.md/#labels) |
| --- | :---: | :---: | :---: | :---: | :---: |
| [Alternate Current](https://www.curseforge.com/minecraft/mc-mods/alternate-current) | Unknown | Alternate Current is an efficient and non-locational redstone dust implementation. | SpaceWalkerRS | Server | None |
| [Mipmaplevel and Language Fix](https://modrinth.com/mod/mipmaplevelandlanguagefix) | Unknown | Makes changing Mipmaplevels and Language faster, by instead of doing a full reload, only reloading the respective part of the game. | KingContaria | Client | None |

[![Home](https://i.imgur.com/zGuelkW.png)](/README.md)
