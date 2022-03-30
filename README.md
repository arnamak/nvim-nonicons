# Nerd Font-Friendly nvim-nonicons

## This is a fork

The only difference between this branch and [the original](https://github.com/yamatsum/nvim-nonicons) is that the glyph mappings have been updated so as to not conflict with Nerd Font glyphs.

See also: [nonicons](https://github.com/arnamak/nonicons)

## Summary
Icon set for neovim plugins and settings.
Collection of configurations for [nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons).

## Prerequisites

- [The nonicons glyph set](https://github.com/arnamak/nonicons)
- [nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons)

## Installation
```
use {
  'arnamak/nvim-nonicons',
  requires = {'kyazdani42/nvim-web-devicons'}
}
```

## Usage

You'll need to load the `nonicons` font in your terminal. Different terminal emulators handle this step in different ways.

See the instructions at [nonicons](https://github.com/arnamak/nonicons) for more details.

Once you've done that, this plugin will enable you to `get` icons within your neovim configuration as such:
```lua
local icons = require "nvim-nonicons"

icons.get("file")
```

## Thank yamatsum
- This repo only exists to make my life easier when I inevitably need to do this again after changing my environment. The icons are not mine, the idea isn't mine, and it's extremely unlikely I do anything in terms of maintenance. So if you have a 'thanks' in you, shoot it over to [yamatsum](https://github.com/yamatsum/nonicons)
