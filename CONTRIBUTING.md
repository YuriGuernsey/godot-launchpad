# Contributing

Thanks for helping improve Godot Launchpad.

## Good First Contributions

- Test installs on Windows and Linux.
- Report install or launch failures with OS details.
- Improve README screenshots and setup notes.
- Add safer version cleanup or uninstall controls.
- Polish app icons and desktop packaging.

## Development

```sh
flutter pub get
dart analyze lib/main.dart test/widget_test.dart
flutter test test/widget_test.dart
```

For macOS:

```sh
LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8 flutter build macos --debug
```

## Pull Requests

Keep pull requests focused and describe:

- what changed
- why it changed
- how you tested it
