![YouTube](https://img.shields.io/badge/CodeSmell-%23FF0000.svg?style=plastic&logo=YouTube&logoColor=white)
![YouTubeSubs](https://img.shields.io/youtube/channel/subscribers/UC4S7Fm5x-WXRCWP6MjK6k2A?style=social)
![Neovim](https://img.shields.io/badge/editor-Neovim-green?logo=neovim&style=plastic)
![Rust](https://img.shields.io/badge/Rust-%23000000.svg?style=plastic&logo=rust&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-%232C2D72.svg?style=plastic&logo=lua&logoColor=white)
![Brave](https://img.shields.io/badge/Brave-FB542B?style=plastic&logo=Brave&logoColor=white)
<img align="right" width="100" height="100" src="https://user-images.githubusercontent.com/8049061/155224899-71324823-4cc0-431a-90e5-63e3c51af05f.png">
# The Official Organization of Code Smell 💩

- **[youtube.com/CodeSmell](https://www.youtube.com/CodeSmell)**
- **[Dotfiles](https://github.com/whatsthatsmell/dots)**

### RustyNews:
- **[Announcing Rust 1.66.1 Stable](https://blog.rust-lang.org/2023/01/10/Rust-1.66.1.html)** 🦀
- [rust-analyzer joins the Rust organization!](https://blog.rust-lang.org/2022/01/20/Rust-1.58.1.html)
- [quick note](https://github.com/whatsthatsmell/q-note) 🦀⚙ -- a little Rust WIP from 💩-- contributions welcomed
### NeoNews:
- Neovim 0.8 is released! → Get it [here](https://github.com/neovim/neovim/releases/tag/v0.8.0) 
- [Global Status](https://github.com/neovim/neovim/commit/5ab122917474b3f9e88be4ee88bc6d627980cfe0) **[Goodness](https://github.com/nvim-lualine/lualine.nvim/pull/613)**!
- This `NVim` → `cmp` plugin is a game changer for Rust devs: [crates.nvim: manage crates.io dependencies](https://github.com/Saecki/crates.nvim)

<br>

**Some Lua key mapping goodness for your Neovim config:**

```lua
-- Replace word under cursor in Buffer (case-sensitive)
-- nmap <leader>sr :%s/<C-R><C-W>//gI<left><left><left>
vim.api.nvim_set_keymap("n", "<leader>sr", ":%s/<C-R><C-W>//gI<left><left><left>", { noremap = false })

-- Replace word under cursor on Line (case-sensitive)
-- nmap <leader>sl :s/<C-R><C-W>//gI<left><left><left>
vim.api.nvim_set_keymap("n", "<leader>sl", ":s/<C-R><C-W>//gI<left><left><left>", { noremap = false })
```

**Neovim Telescope is the superpower you need: https://git.io/telescope999 🔭**

**Proud Sponsor of [Neovim](https://github.com/neovim)**

**Sponsor us by clicking the `Sponsor` button above or at https://paypal.me/CodeSmell**

