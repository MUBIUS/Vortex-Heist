
UNITY UNIVERSAL TEMPLATE - README

This is a standard folder structure template for Unity projects designed to support:
- 2D & 3D Games
- Mobile, PC, Console, Web, and VR platforms

------------------------------------------------------------------------------------
FOLDER STRUCTURE GUIDE:

Assets/
├── _Project/                ← All your game-specific content
│   ├── Art/                 ← Visual content
│   │   ├── Characters/      ← 2D sprites or 3D models of characters
│   │   ├── Environments/    ← Backgrounds, terrains, scenery
│   │   ├── Props/           ← Items, pickups, obstacles
│   │   └── UI/              ← UI design assets (non-functional)
│   ├── Audio/               ← Game audio
│   │   ├── Music/           ← Background music
│   │   ├── SFX/             ← Sound effects
│   │   └── Voice/           ← Voiceovers or dialogues
│   ├── Code/                ← All scripts
│   │   ├── Core/            ← General utilities, helpers, core classes
│   │   ├── Systems/         ← Game systems like Inventory, Dialogue, Save System
│   │   ├── Gameplay/        ← Game-specific logic (player, AI, combat)
│   │   ├── UI/              ← UI logic and script controllers
│   │   └── Editor/          ← Editor scripts and custom tools
│   ├── Materials/           ← Materials for 3D models
│   ├── Prefabs/             ← Reusable object templates
│   │   ├── Characters/      ← Character prefabs
│   │   ├── Props/           ← Item prefabs
│   │   └── UI/              ← UI prefabs like panels or buttons
│   ├── Scenes/              ← Game scenes
│   │   ├── MainMenu/        ← Menus and UI entry points
│   │   ├── Levels/          ← Game levels or maps
│   │   └── Testing/         ← Test or sandbox scenes
│   ├── ScriptableObjects/  ← Unity ScriptableObject assets
│   ├── Shaders/             ← Custom shaders
│   └── UI/                  ← Functional UI components
│       ├── Canvases/        ← Unity UI canvases
│       ├── Fonts/           ← Fonts for UI
│       ├── Icons/           ← UI icons
│       └── Sprites/         ← UI sprites
├── _ThirdParty/             ← External tools, SDKs, assets from Asset Store
├── _Platform/               ← Platform-specific content
│   ├── Mobile/              ← Mobile-only configurations/assets
│   ├── PC/                  ← PC-specific assets
│   └── Console/             ← Console SDKs, configs
├── _Editor/                 ← Project-wide editor extensions

ProjectSettings/             ← Unity generated. Do not edit manually.
Packages/                    ← Unity generated. Do not edit manually.
Documentation/               ← Design docs, workflow notes, guidelines.

------------------------------------------------------------------------------------
NOTES:
- Keep folders organized.
- Don't mix platform-specific assets into shared folders.
- Use Prefabs and ScriptableObjects to improve performance and manageability.

Happy Developing!
