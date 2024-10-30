# Solarized for Obsidian

> Precision colors for machines and people

This is a recolor for [Obsidian](https://obsidian.md/) based on [Ethan Schoonover's Solarized color scheme](https://ethanschoonover.com/solarized/). Works as of Obsidian v1.0.0[^1].

If anything is not working for you, please let me know [here](https://github.com/harmtemolder/obsidian-solarized/issues).

[^1]: Older versions of Obsidian might still be able to use the old `obsidian.css`, but there won't be any support going forward.


## About Solarized

Some outtakes from [Ethan Schoonover's full write-up](https://ethanschoonover.com/solarized/#features):

> Solarized reduces _brightness contrast_ but, unlike many low contrast colorschemes, retains _contrasting hues_ (based on colorwheel relations) for syntax highlighting readability.

> Solarized retains the same selective contrast relationships and overall feel when switching between the light and dark background modes. A _lot_ of thought, planning and testing has gone into making both modes feel like part of a unified colorscheme.

> The monotones have symmetric CIELAB lightness differences, so switching from dark to light mode retains the same perceived contrast in brightness between each value. Each mode is equally readable. The accent colors are based off specific colorwheel relations and subsequently translated to CIELAB to ensure perceptual uniformity in terms of lightness.

## Features

- This theme respects Obsidian's accent color setting, so you can set that to any of [Solarized's accent colors](https://ethanschoonover.com/solarized/#the-values). This is then used to color UI elements and checkboxes, among others.

## Screenshots

### Light

![Solarized light for Obsidian](./screenshot-light.png)

### Dark

![Solarized dark for Obsidian](./screenshot-dark.png)

## How to install

Find this theme in the Obsidian's community themes browser under Settings > Appearance > Themes. If that doesn't work, double-check if you are running the latest version of Obsidian.

## How to develop

Make changes in the `scss` files and compile `theme.scss` into `theme.css` using something like [dart-sass](https://sass-lang.com/dart-sass/).

I use the `.vscode/tasks.json` to compile with <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>B</kbd> in [VSCodium](https://github.com/VSCodium/vscodium#readme).

Don't forget to update the version number in `manifest.json`.

You can add a tag to a commit with `git tag v1.0.10`. Then `git push origin main --tags`.
