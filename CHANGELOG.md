### 2.0.2: 2025-10-27

* Add nvim-treesitter plugin for better syntax highlighting and code understanding with auto-parser directory creation
* Add Cmd+Click to open URLs in default browser on macOS (WezTerm)
* Enable cursorline in nvim to highlight current line
* Add Claude Code integration with automatic Code::Stats XP tracking via hooks
* Add claude-code directory with codestats-hook.sh and secrets management
* Add XP logging to ~/.claude/codestats-hook.log with timestamps
* Add yellow ASCII box WezTerm overlay notifications showing XP (1 XP per line written by Claude)
* Add simple code-stats implementation for nvim without external dependencies
* Add Cmd+V paste and Cmd+C copy keybindings for macOS in wezterm
* Add Telescope search keymaps (<leader>s prefix for search operations)
* Fix gamify streak recalculation on nvim startup (handles Syncthing sync and DST transitions)
* Set leader key to space in nvim
* Increase bottom padding in wezterm for macOS (0.5cell → 1.5cell)
* Update .gitignore to exclude claude-code/secrets.sh
* Update starship.toml, show full path

### 2.0.1: 2025-10-26

* Add hyprland config
* Add barbar for nvim with custom styling (dim grey background, purple bottom border for active tab)
* Configure barbar to auto-hide when only one buffer is open
* Add Ctrl+T keybinding to open new tab
* Remove minimap plugin (wfxr/minimap.vim)
* Add neo-tree as default file explorer
* Add oklch-color-picker plugin for color picking
* Fix Code::Stats integration (custom XP submission workaround for broken plugin)
* Add Code::Stats XP display in lualine statusline with yellow color
* Fix CTRL + SHIFT + E (toggle neo-tree) and CTRL + SHIFT + A (toggle Trouble diagnostics) keybindings
* Configure WezTerm to pass through Ctrl+Shift+A and Ctrl+Shift+E to Neovim
* Set Trouble and neo-tree to load on startup (not lazy-loaded)
* Add luacheck compliance to keymaps configuration
* Remove nodeadkeys (too used to Mac's tilde with space)
* Update Hyprland config to use WezTerm instead of Ghostty (terminal variable, IRC autostart, restore-layout.sh)
* Disable hyprsession in Hyprland config
* Simplify connect-irc.sh script (remove manual window positioning)
* Remove redundant launch-ssh-tmux.sh script
* Add bash tab completion with trailing slashes for directories

### 2.0.0: 2025-10-26

* Revamp dotfiles after years of hiatus
* Release directly 2.0.0
* Open CHANGELOG.md
* Release os-specific wezterm and nvim settings
