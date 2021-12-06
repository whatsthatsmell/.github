![YouTube](https://img.shields.io/badge/CodeSmell-%23FF0000.svg?style=plastic&logo=YouTube&logoColor=white)
![Neovim](https://img.shields.io/badge/editor-Neovim-green?logo=neovim&style=plastic)
![Rust](https://img.shields.io/badge/Rust-%23000000.svg?style=plastic&logo=rust&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-%232C2D72.svg?style=plastic&logo=lua&logoColor=white)
![Brave](https://img.shields.io/badge/Brave-FB542B?style=plastic&logo=Brave&logoColor=white)

# The Official Organization of Code Smell 💩

- **[youtube.com/CodeSmell](https://www.youtube.com/CodeSmell)**
- **[Dotfiles](https://github.com/whatsthatsmell/dots)**

### NeoNews:
- [Neovim 0.6 has released](https://github.com/neovim/neovim/releases/tag/v0.6.0)
- 🔭 [Telescope's `builtin.file_browser` will be removed December 19th](https://github.com/nvim-telescope/telescope.nvim/issues/1470#issuecomment-974147513)
  - See the [migration](https://github.com/whatsthatsmell/dots/commit/0066a230a365bbd367ccd072e970b5c3ab276d86) in the Dotfiles

### RustyNews:
- [Rust 1.57.0 Stable Released](https://blog.rust-lang.org/2021/12/02/Rust-1.57.0.html) *_you should use nightly though_
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

**Proud [Sponsor](https://github.com/joelpalmer?tab=sponsoring) of [Neovim](https://github.com/neovim) and [Rust Analyzer](https://github.com/rust-analyzer) and others!**

**Sponsor us by clicking the `Sponsor` button above or at https://paypal.me/CodeSmell**

