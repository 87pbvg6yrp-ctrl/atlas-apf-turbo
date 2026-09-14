# ATLAS APF TURBO

**High-speed deterministic No Man's Sky planet and system finder for Windows.**

ATLAS APF TURBO searches deterministic No Man's Sky generation data at high speed and lets you narrow results using planet, system, moon, relationship, colour, terrain, weather, water, resource, Sentinel and structural filters.

**Current release:** `1.2.3`  
**Platform:** Windows 10/11 x64  
**CPU requirement:** AVX2-capable x64 processor

> ATLAS APF TURBO is an independent community tool. It is not affiliated with or endorsed by Hello Games.

## Download

Use the repository's **Releases** section and download the latest Windows public ZIP.

For v1.2.3, the release asset is:

```text
ATLAS-APF-TURBO-1.2.3-Windows-x64-PUBLIC.zip
```

Extract the ZIP, then run:

```text
ATLAS_APF_TURBO.exe
```

No Python installation, Visual Studio installation, administrator access, setup wizard, or running No Man's Sky process is required.

## Main features

- High-speed deterministic planet and system searching.
- Planet filters for biome, classification, sub-biome, terrain, colours, weather, water, resources, Sentinel conditions and more.
- System and moon structural filters.
- Result-planet relationship filters, including parent/moon relationships and body-count constraints.
- Search scopes for result planets, planets in a system, moons in a system, moons orbiting the result planet, and all bodies in a system.
- Constraint-aware filter choices that remove combinations proven impossible by the current selections.
- Randomise Anchor Region control for quickly moving to a different valid search region.
- Fast result paging and responsive Start/Stop controls for large searches.
- CSV export.
- APFZ lossless archives with exact reconstruction support.
- APFZ compatibility with versions 1.2.2, 1.2.1, 1.2.0, 1.1.0 and 1.0.0.

## Version 1.2.3 highlights

Version 1.2.3 focuses on field-feedback corrections, filter safety and usability while preserving deterministic output contracts.

- Hardened relationship-filter validation to prevent impossible parent/moon combinations reaching the runtime.
- Added **Randomise Anchor Region**.
- Clarified `Clear` and `Humid` weather labels with biome context.
- Reclassified exact sky colour `#4AC0FF` into the Cyan family and display it as `Cyan-blue #4AC0FF`.
- Clarified generated water palette input versus exact water appearance style.
- Retained exact deterministic system and relationship output contracts through the optimization/release gates.

See [CHANGELOG.md](CHANGELOG.md) for release history.

## Accuracy and generated-vs-rendered values

APF is designed around deterministic game-generation data. Some generated values are not the same thing as final rendered appearance.

Where that distinction is known, the UI attempts to state it explicitly. For example, generated water palette input is presented separately from exact water appearance style.

If you find a real in-game result that disagrees with APF, please use the **Incorrect result / classification** issue template and include the portal address, galaxy, APF version, selected filters and screenshots where possible.

## Requirements

- Windows 10 or Windows 11, 64-bit.
- x64 processor with AVX2 support.

## Installation

1. Open **Releases**.
2. Download the newest `Windows-x64-PUBLIC.zip` asset.
3. Extract the ZIP to a normal folder.
4. Keep `ATLAS_APF_TURBO.exe`, `README.txt` and `VERSION.txt` together.
5. Double-click `ATLAS_APF_TURBO.exe`.

## Reporting bugs and requesting features

Use the repository's **Issues** tab.

Three templates are provided:

- **Bug report** — crashes, broken controls, export problems and other software defects.
- **Incorrect result / classification** — APF result differs from the game or from a reproducible deterministic expectation.
- **Feature request** — new filters, quality-of-life improvements or workflow ideas.

Please do not include private account information, save files containing personal data, access tokens, passwords or other secrets in public issues.

## Repository scope

This repository currently hosts public documentation, issue tracking and release downloads for ATLAS APF TURBO.

The application source code and internal build/research datasets are **not currently published in this repository**.

## Credits

ATLAS APF TURBO is developed by **FIBONACCI**, with community field testing and feedback contributing to validation and usability improvements.

## Disclaimer

No Man's Sky and related names are property of their respective owners. ATLAS APF TURBO is an independent community project and is not affiliated with or endorsed by Hello Games.
