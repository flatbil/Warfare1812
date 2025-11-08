# Warfare 1812
This repository serves as a hub for development ideas for the a game based on the time period of the War of 1812

Short description
A hero-led, "Micro RTS" set in the early 19th-century North American frontier. Play as a frontiersman and commander of small, specialized detachments (Rangers, militia, privateers). Emphasis on Rogers’ Rules of Ranging, riverine/naval ops (gunboats, skiffs), and a dynamic sandbox around the War of 1812.

Repository layout
- `Assets/`        - Unity assets (art/audio symlinked if needed)
- `ProjectSettings/` - Unity project settings
- `Scripts/`       - Game code (C#)
- `Prototypes/`    - Prototype scenes & quick test builds
- `Docs/`          - Design docs, GDD, rules mapping
- `Builds/`        - Local build artifacts (ignored)
- `Tools/`         - Editor utilities and scripts

Development notes
- Engine: Unity (recommended for Apple Silicon)
- Local dev machine: macOS (M4 Mac Mini). Keep Editor and ProjectSettings on internal SSD; use symlinks for large asset folders to an external 2 TB drive.
- Version control: `git` + `git-lfs` for large assets. Avoid committing `/Library/` or built artifacts.

Getting started (dev)
1. Install Unity (recommend 2021.3 LTS or newer with Apple Silicon support).
2. Install Git LFS: `git lfs install`.
3. Create symlinks for large asset folders if storing assets externally:
   `ln -s /Volumes/ExternalDrive/MyGameAssets ~/Projects/MyGame/Assets`
4. Open the Unity project from the repo root and run the `Prototypes/VerticalSlice` scene for the quick start.

Contributing
- Follow the coding style in `Scripts/` (C# conventions).
- Keep PRs focused and include screenshots/video when adding UI or visual changes.
- Large art/audio files should be added to LFS or stored on the external drive and referenced via symlink.

License
This repository is provisionally licensed under the MIT License. See `LICENSE` for details.

Contacts
- Owner: Your Name (you@domain.com)
