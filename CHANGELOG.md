# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

## [1.1.5] - 2025-08-27

### Fixed

- [Fix Deprecation Warning \[color-functions\] #44](https://github.com/harmtemolder/obsidian-solarized/pull/44)

### Added

- Add the option to disable highlighting the active line with the [Style Settings plugin](https://github.com/mgmeyers/obsidian-style-settings) ([#45](https://github.com/harmtemolder/obsidian-solarized/pull/45))

## [1.1.4] - 2025-06-26

### Fixed

- Fix [Button hover colour is the same as text colour #43](https://github.com/harmtemolder/obsidian-solarized/issues/43)

## [1.1.3] - 2024-12-21

### Fixed

- Fix [#42 No distinction between existing, non-existing notes and regular text](https://github.com/harmtemolder/obsidian-solarized/issues/42)

### Changed

- Color hashtags in dark mode

## [1.1.2] - 2024-12-10

### Fixed

- Fix [#41 Hard to read mermaid](https://github.com/harmtemolder/obsidian-solarized/issues/41)

### Changed

- Add `sass` command to README

## [1.1.1] - 2024-11-04

### Fixed

- Fix support for Obsidian's built-in accent color

### Added

- Add support for the [Style Settings plugin](https://github.com/mgmeyers/obsidian-style-settings)

## [1.1.0] - 2024-11-01

### Added

- Add support for [Vimrc Support plugin](https://github.com/esm7/obsidian-vimrc-support)

### Changed

- Construct colors using SCSS map

## [1.0.10] - 2024-10-30

### Fixed

- Correct text color in community plugin and theme browser search results (see [#35](https://github.com/harmtemolder/obsidian-solarized/issues/35))
- Correct text color in preview mode highlights (see [#35](https://github.com/harmtemolder/obsidian-solarized/issues/35))
- Make links in editor mode landing selection readable
- Make inline code in editor mode landing selection stand out

### Changed

- Split changelog to separate file
- Move to dart-sass

## [1.0.9-beta] - 2023-09-05

### Removed

- Do not use monospace font for editing view (see [#33](https://github.com/harmtemolder/obsidian-solarized/issues/33))

## [1.0.8-beta] - 2023-07-31

### Fixed

- Fix strikethrough of links in editing view

## 1.0.7-beta - 2023-07-24

### Removed

- Do not adjust font sizes
- Delete legacy `obsidian.css`

## [1.0.6-beta] - 2023-07-07

### Added

- Highlight active line in editor
- `.vscode/tasks.json` (see [How to develop](https://github.com/harmtemolder/obsidian-solarized?tab=readme-ov-file#how-to-develop))
- Support for [the Dynamic Highlights plugin](https://github.com/nothingislost/obsidian-dynamic-highlights)
  - Yellow highlights to differentiate from other highlights

### Changed

- Use existing `--code-size` variable for size of monospace fonts in editor and preview
- Color checkboxes in editing view
- Color selected file in file explorer and more contrast when flashing
- More contrast in highlight when clicking from outline tab
- Color search results green to differentiate from other highlights
- Color border of focussed UI element

## 1.0.5-beta - 2022-11-24

### Changed

- Use less pronounced background colors for input elements in settings menu

## 1.0.4-beta - 2022-11-24

### Added

- More consistent colors for internal, unresolved and external links
- Bold table headers

### Changed

- Use accent color for vim cursor
- Use accent color for search results and highlights
- Use accent color for frontmatter dashes and parameters

## 1.0.3-beta - 2022-11-23

### Changed

- Use accent color for checkboxes in both editing and reading view

## 1.0.2-beta - 2022-11-23

### Changed

- Follow [Ethan Schoonover's examples](https://ethanschoonover.com/solarized/#screenshots) more closely for code formatting (fixing [#27](https://github.com/harmtemolder/obsidian-solarized/issues/27))

## 1.0.1-beta - 2022-11-22

### Added

- Orange as default accent color

### Fixed

- Some control elements in the settings menu that were invisible in dark mode

## 1.0.0-beta - 2022-11-22

### Fixed

- Issues caused by Obsidian's upgrade to v1.0.0 ([#23](https://github.com/harmtemolder/obsidian-solarized/issues/23), [#25](https://github.com/harmtemolder/obsidian-solarized/issues/25), [#26](https://github.com/harmtemolder/obsidian-solarized/issues/26), [#27](https://github.com/harmtemolder/obsidian-solarized/issues/27))

### Added

- Changelog

### Changed

- Using SCSS instead of plain CSS for cleaner development
- Overwriting Obsidian's default CSS variables instead of overwriting actual CSS rules, where possible

[1.1.4]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.1.4
[1.1.3]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.1.3
[1.1.2]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.1.2
[1.1.1]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.1.1
[1.1.0]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.1.0
[1.0.10]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.0.10
[1.0.9-beta]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.0.9-beta
[1.0.8-beta]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.0.8-beta
[1.0.6-beta]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.0.6-beta
