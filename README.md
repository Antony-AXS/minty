# Minty

Beautifully crafted color tools for Neovim
 
![shades](https://github.com/user-attachments/assets/d499748b-d9c8-4a92-89ba-bfce1814c275)
![huefy](https://github.com/user-attachments/assets/21f2c23d-94c6-4ccf-a0d0-ddf91f6bb5c1)

## Install

```lua
{ "nvchad/volt", lazy = true },

{
  "nvchad/minty",
  cmd = { "Shades", "Huefy" },
}

```
## Usage

`Shades`, `Huefy` are the commands.

- Check [config table](https://github.com/NvChad/minty/blob/main/lua/minty/init.lua#L3)
- Example opts config

```lua
{
  "nvchad/minty",
  cmd = { "Shades", "Huefy" },
  opts = { huefy = { border = false } }
}
```

Do check the [demo video](https://www.youtube.com/watch?v=NHC4jLoR_zI) to get an overview!

## Mappings ( useful for no-mouse users)

- `<Ctrl> + t` : cycle through windows
- `<Tab>` or `<S-Tab>` : cycle through clickables in current window
- `<CR>` i.e enter to click on the area
- moving cursor with `h` or `l` in slider 
