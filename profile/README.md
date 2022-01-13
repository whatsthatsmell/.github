![YouTube](https://img.shields.io/badge/CodeSmell-%23FF0000.svg?style=plastic&logo=YouTube&logoColor=white)
![YouTubeSubs](https://img.shields.io/youtube/channel/subscribers/UC4S7Fm5x-WXRCWP6MjK6k2A?style=social)
![Neovim](https://img.shields.io/badge/editor-Neovim-green?logo=neovim&style=plastic)
![Rust](https://img.shields.io/badge/Rust-%23000000.svg?style=plastic&logo=rust&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-%232C2D72.svg?style=plastic&logo=lua&logoColor=white)
![Brave](https://img.shields.io/badge/Brave-FB542B?style=plastic&logo=Brave&logoColor=white)

# The Official Organization of Code Smell 💩

- **[youtube.com/CodeSmell](https://www.youtube.com/CodeSmell)**
- **[Dotfiles](https://github.com/whatsthatsmell/dots)**

### NeoNews:
- [Neovim 0.6.1 has released](https://github.com/neovim/neovim/releases/tag/v0.6.1)

### RustyNews:
- [Rust 1.58.0 Stable Released](https://blog.rust-lang.org/2022/01/13/Rust-1.58.0.html) *_you should use nightly though_
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

**Proud Sponsor of [Neovim](https://github.com/neovim) and [Rust Analyzer](https://github.com/rust-analyzer) and others!**

**Sponsor us by clicking the `Sponsor` button above or at https://paypal.me/CodeSmell**

