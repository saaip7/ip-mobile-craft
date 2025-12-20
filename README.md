# Flutter Mobile Design - Claude Code Plugin

A Claude Code skill for creating distinctive, production-grade Flutter mobile applications with Material Design 3.

## Features

- **UI Creation** - Build beautiful Flutter widgets and screens from scratch
- **Design-to-Code** - Convert Figma/mockups to Flutter code
- **Material Design 3** - Full M3 support with ColorScheme, Typography, Components
- **Architecture Patterns** - Riverpod (recommended), BLoC, and clean architecture
- **Best Practices** - Performance optimization, accessibility, platform conventions

## Installation

1. Add the marketplace:
```bash
/plugin marketplace add saaip7/flutter-mobile-design
```

2. Install the skill:
```bash
/plugin install flutter-mobile-design@flutter-mobile-design-marketplace
```

## Usage

Once installed, the skill activates when you ask Claude to:

- "Build a login screen in Flutter"
- "Create a product card widget with Material 3"
- "Convert this Figma design to Flutter"
- "Build a dashboard app with bottom navigation"
- "Create a settings page with dark mode toggle"

## What's Included

```
flutter-mobile-design/
├── .claude-plugin/
│   └── marketplace.json    # Marketplace metadata
├── skills/
│   └── flutter-mobile-design/
│       └── SKILL.md        # Skill instructions
└── README.md
```

## Skill Highlights

### Material Design 3
- Dynamic color with `ColorScheme.fromSeed`
- M3 typography scale
- Updated components (NavigationBar, FilledButton, etc.)
- Motion and elevation guidelines

### State Management
- **Riverpod** as recommended approach
- **BLoC** for enterprise apps
- Clean architecture project structure

### Quality Focus
- Performance optimization tips
- Accessibility guidelines
- Platform-specific considerations (iOS/Android)
- 60fps animation targets

## License

MIT

## Contributing

Contributions welcome! Feel free to open issues or PRs.
