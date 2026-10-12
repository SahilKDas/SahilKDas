# Hey, I’m Sahil 👋

**I build ~~game-playing engines, neural systems, native game ports, languages, and the occasional one-day project~~ whatever I want to build.**

The pattern lately is pretty obvious, though: board-game engines, neural agents, self-play, native tooling, and experiments where the result has to survive contact with actual rules.

> A talent for always being on the spark.
>
> Sometimes I deliver in a day; sometimes I disappear into weeks-long builds.

## What I’m working on now

### [Skallagrim](https://github.com/SahilKDas/Skallagrim) — neural Hnefatafl research

Skallagrim is my Rust/Python Copenhagen Hnefatafl engine and research platform. It has a native `tiny-skia` GUI, a dedicated Rust referee, reproducible match tooling, and three competing neural/search ideas:

- **Rho:** CNN policy/value evaluation with MCTS
- **Iota:** NNUE evaluation with alpha-beta search
- **Beta:** NNUE evaluation with MCTS

The first 750-game campaign is complete, but I’m not turning that into a fake “best engine ever” claim. Timing failures, rules disagreements, and a long-soak timeout still matter. The fun part is building the evidence, not just posting the largest number.

### [tangOS-Native](https://github.com/SahilKDas/tangOS-Native) — decompilation tooling without the browser tax

I’m working on a native fork of [tangosdev/tangOS](https://github.com/tangosdev/tangOS). The main focus is **TangOS Lite**: a portable C++/Win32/TinySkia workbench for decompilation repositories, reviewed Git operations, GitHub integration, live progress, and repeatable release checkpoints.

The original project and retained web implementation remain credited and useful as the parity reference. “It builds” is not the same thing as “native parity is complete.”

### [OpenShobu](https://github.com/OpenShobu) — giving a niche board game real developer infrastructure

I’m also working on Shōbu tooling through OpenShobu:

- **[Universal Shōbu Protocol Specifications](https://github.com/OpenShobu/Universal-Shobu-Protocol-Specifications):** formal rules, SFEN state serialization, SSGF saved games, USP 1.0, conformance tests, and examples in six languages.
- **[cani](https://github.com/OpenShobu/cani):** a dependency-free Rust rules SDK with a C ABI, a C++26 value wrapper, and a protocol engine.

### The native-port lane

- **[MK7-Native](https://github.com/SahilKDas/MK7-Native)** now reaches scene-geometry submission and real pixel output, with PICA vertex loading, texture/TEV decoding, HID progress, persistent saves, and synchronized presentation.
- **[64DS-DX](https://github.com/SahilKDas/64DS-DX)** stays synchronized with the credited SM64DS decompilation/co-op foundations while I work on port integration and additions such as fifth-character support.

## Shipped, archived, or still mutating

- **[Genseki](https://github.com/SahilKDas/Genseki)** is over and archived. Alpha won the argument; my learned Nu line never beat it. The engine, GUI, review tooling, gauntlets, evidence, and failed neural research stay public.
- **[LFE-NNUE](https://github.com/SahilKDas/LFE-NNUE)** shipped a native v1.0 evolutionary ecosystem—and apparently “complete” still left room for deterministic 2.5D habitats and elevation.
- **[Eloi](https://github.com/SahilKDas/Eloi/tree/v4.0.0)** remains paused until somebody takes on its four-player Kaggle program.
- **[SM3DL-Recomp](https://github.com/SahilKDas/SM3DL-Recomp)** is still a January 2027 project, not fake progress wearing a README.

## The stuff I reach for

`Rust` · `C++` · `Python` · `TypeScript` · `JavaScript` · `Vulkan` · `TinySkia` · `CMake` · `Cargo` · `Bun`

I like neural systems, engine architecture, reproducible experiments, native applications, and honest failure reports. I also like everything else, as long as everything else likes me back.

## Where I’m going

I **will apply to Google DeepMind**.

Until then, I’m turning the gap between curiosity and research engineering into public work I can explain: the rules, the data, the model, the evaluation, the failure, and the system around it.

## Say hi on Discord

I’m open to software-engineering roles, open-source collaboration, and developer friends who enjoy difficult or slightly weird projects.

- **Portfolio:** [sahilkdas.github.io](https://sahilkdas.github.io/)
- **Discord:** `lordhank2`
- **Chess.com:** [sahildas34](https://www.chess.com/member/sahildas34)
