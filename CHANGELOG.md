# Change Log

## [0.1.0] - 2023-01-09

- Initial release

## [0.1.1] - 2023-01-09

- Improved: Better handling and warning info if extensions.json is missing when running the extension

## [0.1.2] - 2023-01-09

- Fixed: Bug when `.vscode/extensions.json` existed but without any `unwantedRecommendations` set.

## [0.1.3] - 2023-01-09

- Added: Extension Icon

## [0.2.0] - 2023-01-09

- Change: Inverted the icon

## [0.3.0] - 2023-01-26

- README updated

## [0.4.0] - 2023-02-24

- Added: Supporting workspace settings (multi-root): define extensions in `***.code-workspace` file
- Improved: Lowering verbosity of some output

## [0.5.0] - 2023-07-26

- Added: Supporting semver versions for unwantedRecommendations in the new `extensionsVersionCheck.json` file.
- Added: New warnings if the semver versions do match the installed version
