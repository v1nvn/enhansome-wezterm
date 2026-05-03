<!-- lint ignore awesome-git-repo-age -->

# Awesome WezTerm [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 461,711 | 🐛 70 | 📅 2026-04-19 with stars

<img src="https://raw.githubusercontent.com/wez/wezterm/main/assets/icon/wezterm-icon.svg" align="right" width="144" />

> Collections of awesome WezTerm plugins. [Plugin Guide](https://github.com/wezterm/wezterm/blob/main/docs/config/plugins.md) ⭐ 25,895 | 🐛 1,710 | 🌐 Rust | 📅 2026-05-01. Found something cool? Please [contribute](origin/CONTRIBUTING.md)!

[WezTerm](https://wezfurlong.org/wezterm/) is a powerful cross-platform terminal emulator and multiplexer written by [@wez](https://github.com/wez) and implemented in [Rust](https://www.rust-lang.org).

To enhance your WezTerm configuration experience:

* [DrKJeff16/wezterm-types](https://github.com/DrKJeff16/wezterm-types) ⭐ 196 | 🐛 1 | 🌐 Lua | 📅 2026-04-30 - WezTerm type annotations that can be added as a completion source in your editor to provide code assistance when working with WezTerm's Lua API. Includes community plugins support.

## Contents

* [AI](#ai)
* [Keybinding](#keybinding)
* [Media](#media)
* [Neovim](#neovim)
* [Panes](#panes)
* [Session](#session)
* [Tab bar](#tab-bar)
* [Themes](#themes)
* [Utility](#utility)

## AI

* [Eric162/wezterm-agent-deck](https://github.com/Eric162/wezterm-agent-deck) ⭐ 53 | 🐛 0 | 🌐 Lua | 📅 2026-03-26 - Monitors AI coding agents, shows status dots in tabs and notifications when agents need attention.
* [Michal1993r/ai-helper.wezterm](https://github.com/Michal1993r/ai-helper.wezterm/tree/master) ⭐ 37 | 🐛 1 | 🌐 Lua | 📅 2026-03-13 - Ask AI for CLI help with LM Studio or Google Gemini.
* [dimao/ai-commander.wezterm](https://github.com/dimao/ai-commander.wezterm) ⭐ 7 | 🐛 1 | 🌐 Lua | 📅 2025-08-24 - Generate and select bash commands based on natural language prompts.
* [EdenGibson/wezterm-quota-limit](https://github.com/EdenGibson/wezterm-quota-limit) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2026-04-20 - Shows Claude API usage quota in the status bar with color-coded thresholds and automatic token refresh.

## Keybinding

* [MLFlexer/modal.wezterm](https://github.com/MLFlexer/modal.wezterm) ⭐ 119 | 🐛 3 | 🌐 Lua | 📅 2025-06-30 - Predefined Vim-like modal keybindings with a good looking UI.
* [sei40kr/wez-tmux](https://github.com/sei40kr/wez-tmux) ⭐ 51 | 🐛 1 | 🌐 Lua | 📅 2025-11-03 - Ported tmux keybindings.
* [abidibo/wezterm-cmdpicker](https://github.com/abidibo/wezterm-cmdpicker) ⭐ 10 | 🐛 1 | 🌐 Lua | 📅 2026-03-11 - Add a command-palette-style fuzzy picker for keybindings. Press a trigger key to search and execute any keybinding — user-defined, config, or WezTerm defaults.
* [sei40kr/wez-pain-control](https://github.com/sei40kr/wez-pain-control?tab=readme-ov-file) ⭐ 9 | 🐛 0 | 🌐 Lua | 📅 2023-11-21 - Pane control keybindings like tmux-pain-control.
* [selectnull/pinned-tabs.wezterm](https://github.com/selectnull/pinned-tabs.wezterm) ⭐ 3 | 🐛 0 | 🌐 Lua | 📅 2025-08-16 - Lets you assign a key binding to a specific tab.

## Media

* [xarvex/presentation.wez](https://github.com/xarvex/presentation.wez) ⭐ 19 | 🐛 0 | 🌐 Lua | 📅 2024-09-12 - Rather simple presentation mode toggle.

## Neovim

* [mrjones2014/smart-splits.nvim](https://github.com/mrjones2014/smart-splits.nvim) ⭐ 1,639 | 🐛 16 | 🌐 Lua | 📅 2026-05-01 - Provides an addon for seamless pane navigation between Neovim and the WezTerm MUX.
* [winter-again/wezterm-config.nvim](https://github.com/winter-again/wezterm-config.nvim) ⭐ 72 | 🐛 2 | 🌐 Lua | 📅 2026-04-01 - Interact with the WezTerm configuration directly from Neovim.

## Panes

* [ChrisGVE/pivot\_panes.wezterm](https://github.com/ChrisGVE/pivot_panes.wezterm) ⭐ 6 | 🐛 0 | 🌐 Lua | 📅 2026-03-06 - Toggle pane orientation between horizontal and vertical splits.
* [bad-noodles/stack.wez](https://github.com/bad-noodles/stack.wez) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2025-11-23 - Stacked pane mode, work with multiple panes but see only one at a time.

## Session

* [MLFlexer/resurrect.wezterm](https://github.com/MLFlexer/resurrect.wezterm) ⭐ 299 | 🐛 38 | 🌐 Lua | 📅 2025-07-04 - Save and restore the state of windows, tabs and panes.
* [MLFlexer/smart\_workspace\_switcher.wezterm](https://github.com/MLFlexer/smart_workspace_switcher.wezterm) ⭐ 196 | 🐛 3 | 🌐 Lua | 📅 2025-06-30 - Switch between workspaces with fuzzy finding and `zoxide`.
* [mikkasendke/sessionizer.wezterm](https://github.com/mikkasendke/sessionizer.wezterm) ⭐ 91 | 🐛 1 | 🌐 Lua | 📅 2025-07-05 - Opening Git repositories as their own WezTerm workspaces using `fd`.
* [DavidRR-F/quick\_domains.wezterm](https://github.com/DavidRR-F/quick_domains.wezterm) ⭐ 27 | 🐛 4 | 🌐 Lua | 📅 2026-02-01 - Faster way to search and attach to (SSH) domains.
* [abidibo/wezterm-sessions](https://github.com/abidibo/wezterm-sessions) ⭐ 22 | 🐛 1 | 🌐 Lua | 📅 2026-03-28 - Save and restore sessions.
* [vieitesss/workspacesionizer.wezterm](https://github.com/vieitesss/workspacesionizer.wezterm) ⭐ 18 | 🐛 0 | 🌐 Lua | 📅 2026-03-03 - Blazingly fast workspace chooser inspired by `tmux-sessionizer`.
* [isseii10/workspace-picker.wezterm](https://github.com/isseii10/workspace-picker.wezterm) ⭐ 6 | 🐛 2 | 🌐 Lua | 📅 2026-01-11 - Workspace switcher with `zoxide` integration.
* [JuanraCM/wsinit.wezterm](https://github.com/JuanraCM/wsinit.wezterm) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2026-03-02 - A simple and flexible way to manage and initialize workspace configurations.
* [srackham/tabsets.wezterm](https://github.com/srackham/tabsets.wezterm) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2025-12-27 - Load, save, rename and delete named sets of tabs.

## Tab bar

* [michaelbrusegard/tabline.wez](https://github.com/michaelbrusegard/tabline.wez) ⭐ 293 | 🐛 6 | 🌐 Lua | 📅 2026-02-13 - A versatile and easy to use retro tab bar with the `lualine.nvim` configuration format.
* [adriankarlen/bar.wezterm](https://github.com/adriankarlen/bar.wezterm) ⭐ 223 | 🐛 1 | 🌐 Lua | 📅 2026-04-15 - A configurable tab bar with batteries included.
* [yriveiro/wezterm-tabs](https://github.com/yriveiro/wezterm-tabs) ⭐ 27 | 🐛 1 | 🌐 Lua | 📅 2026-03-23 - Configurable tabs for the retro tab bar.
* [yriveiro/wezterm-status](https://github.com/yriveiro/wezterm-status) ⭐ 26 | 🐛 0 | 🌐 Lua | 📅 2026-03-23 - Configurable status for the retro tab bar.
* [rootiest/battery.wez](https://github.com/rootiest/battery.wez) ⭐ 10 | 🐛 0 | 🌐 Lua | 📅 2024-10-07 - A colorful and fancy battery component for the retro tab bar.

## Themes

* [neapsix/wezterm](https://github.com/neapsix/wezterm) ⭐ 75 | 🐛 0 | 🌐 Lua | 📅 2024-05-11 - Rosé Pine theme, all natural pine, faux fur and a bit of soho vibes.
* [koh-sh/wezterm-theme-rotator](https://github.com/koh-sh/wezterm-theme-rotator) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2025-03-23 - Cycle through built-in themes using keyboard shortcuts.
* [sravioli/kanagawa.wz](https://github.com/sravioli/kanagawa.wz) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2026-04-10 - Kanagawa.nvim color schemes with Wave, Dragon, and Lotus variants.

## Utility

* [zsh-sage/toggle\_terminal.wez](https://github.com/zsh-sage/toggle_terminal.wez) ⭐ 23 | 🐛 0 | 🌐 Lua | 📅 2025-10-22 - An easy-to-use toggleable terminal window.
* [ChrisGVE/listeners.wezterm](https://github.com/ChrisGVE/listeners.wezterm) ⭐ 13 | 🐛 0 | 🌐 Lua | 📅 2026-03-06 - Enables enhanced event listener capabilities with persistent state management.
* [ChrisGVE/lib.wezterm](https://github.com/ChrisGVE/lib.wezterm) ⭐ 8 | 🐛 0 | 🌐 Lua | 📅 2026-03-06 - A library of common utility functions for plugin developers.
* [ChrisGVE/dev.wezterm](https://github.com/ChrisGVE/dev.wezterm) ⭐ 7 | 🐛 1 | 🌐 Lua | 📅 2026-03-06 - Location resolver for development and deployment of a plugin.
* [quantonganh/quickselect.wezterm](https://github.com/quantonganh/quickselect.wezterm) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2025-12-13 - Jump to the build error by opening them in Helix.
* [aureolebigben/wezterm-cmd-sender](https://github.com/aureolebigben/wezterm-cmd-sender) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2026-04-19 - Send commands to multiple panes.
* [sravioli/memo.wz](https://github.com/sravioli/memo.wz) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2026-04-10 - Memoization, caching, and persistent state management.
* [sravioli/warp.wz](https://github.com/sravioli/warp.wz) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2026-04-10 - General-purpose utility library with string, table, list, path, and filesystem helpers.
* [btrachey/wezterm-replay](https://github.com/btrachey/wezterm-replay) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2025-09-18 - Parse command output and get URLs, shell commands, etc. pasted into your next prompt.
* [sravioli/log.wz](https://github.com/sravioli/log.wz) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2026-04-02 - Tagged logging library with pluggable sinks and severity thresholds.
* [lilaqua/tunicodes](https://gitlab.com/lilaqua/tunicodes) - Insert Unicode characters via their codepoints.
