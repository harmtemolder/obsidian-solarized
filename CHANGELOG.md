# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

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
- `.vscode/tasks.json` (see [How to develop](#how-to-develop))
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

- [Changelog](#changelog)

### Changed

- Using SCSS instead of plain CSS for cleaner development
- Overwriting Obsidian's default CSS variables instead of overwriting actual CSS rules, where possible

[1.0.9-beta]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.0.9-beta
[1.0.8-beta]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.0.8-beta
[1.0.6-beta]: https://github.com/harmtemolder/obsidian-solarized/releases/tag/v1.0.6-beta
