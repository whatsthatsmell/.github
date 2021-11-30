![YouTube](https://img.shields.io/badge/CodeSmell-%23FF0000.svg?style=plastic&logo=YouTube&logoColor=white)
![Neovim](https://img.shields.io/badge/editor-Neovim-green?logo=neovim&style=plastic)
![Rust](https://img.shields.io/badge/Rust-%23000000.svg?style=plastic&logo=rust&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-%232C2D72.svg?style=plastic&logo=lua&logoColor=white)
![Brave](https://img.shields.io/badge/Brave-FB542B?style=plastic&logo=Brave&logoColor=white)

# The Official Organization of Code Smell 💩

- **[youtube.com/CodeSmell](https://www.youtube.com/CodeSmell)**
- **[Dotfiles](https://github.com/whatsthatsmell/dots)**

### NeoNews:
- [Neovim 0.6 release stream TODAY (11/30/21 at 17:00 UTC/12:00 pm EST)](https://neovim.discourse.group/t/neovim-0-6-release-stream-11-30-21-at-17-00-utc-12-00-pm-est/1535)
- 🔭 [Telescope's `builtin.file_browser` will be removed December 19th](https://github.com/nvim-telescope/telescope.nvim/issues/1470#issuecomment-974147513)

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

**Proud Sponsor of [Neovim](https://github.com/neovim) and [Rust Analyzer](https://github.com/rust-analyzer)**

**Sponsor us by clicking the `Sponsor` button above or at https://paypal.me/CodeSmell**

