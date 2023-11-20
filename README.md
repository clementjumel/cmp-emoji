# cmp-gitmoji

nvim-cmp source for gitmojis.

This plugin is a fork of [cmp-emoji](https://github.com/hrsh7th/cmp-emoji), where the emojis list
has been curated manually to match [gitmojis](https://gitmoji.dev/) (extra emojis have been removed,
missing ones have been added, and some have been fixed).

# Setup

```lua
require'cmp'.setup {
  sources = {
    { name = 'gitmoji' }
  }
}
```

# Option

#### insert (type: boolean)

Speficy gitmoji should be insert or not.

Default: `false`
