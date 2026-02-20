<!-- lint ignore awesome-git-repo-age -->

# Awesome WezTerm [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 438,706 | 🐛 70 | 📅 2026-01-28 with stars

<img src="https://raw.githubusercontent.com/wez/wezterm/main/assets/icon/wezterm-icon.svg" align="right" width="144" />

> Collections of awesome WezTerm plugins. [Plugin Guide](https://github.com/wezterm/wezterm/blob/main/docs/config/plugins.md) ⭐ 24,338 | 🐛 1,603 | 🌐 Rust | 📅 2026-02-05. Found something cool? Please [contribute](origin/CONTRIBUTING.md)!

[WezTerm](https://wezfurlong.org/wezterm/) is a powerful cross-platform terminal emulator and multiplexer written by [@wez](https://github.com/wez) and implemented in [Rust](https://www.rust-lang.org).

To enhance your WezTerm configuration experience:

* [DrKJeff16/wezterm-types](https://github.com/DrKJeff16/wezterm-types) ⭐ 170 | 🐛 2 | 🌐 Lua | 📅 2026-02-20 - WezTerm type annotations that can be added as a completion source in your editor to provide code assistance when working with WezTerm's Lua API. Includes community plugins support.

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

* [Michal1993r/ai-helper.wezterm](https://github.com/Michal1993r/ai-helper.wezterm/tree/master) ⭐ 24 | 🐛 1 | 🌐 Lua | 📅 2026-01-14 - Ask AI for CLI help with LM Studio or Google Gemini.
* [Eric162/wezterm-agent-deck](https://github.com/Eric162/wezterm-agent-deck) ⭐ 21 | 🐛 0 | 🌐 Lua | 📅 2026-01-20 - Monitors AI coding agents, shows status dots in tabs and notifications when agents need attention.
* [dimao/ai-commander.wezterm](https://github.com/dimao/ai-commander.wezterm) ⭐ 3 | 🐛 1 | 🌐 Lua | 📅 2025-08-24 - Generate and select bash commands based on natural language prompts.

## Keybinding

* [MLFlexer/modal.wezterm](https://github.com/MLFlexer/modal.wezterm) ⭐ 111 | 🐛 3 | 🌐 Lua | 📅 2025-06-30 - Predefined Vim-like modal keybindings with a good looking UI.
* [sei40kr/wez-tmux](https://github.com/sei40kr/wez-tmux) ⭐ 43 | 🐛 1 | 🌐 Lua | 📅 2025-11-03 - Ported tmux keybindings.
* [sei40kr/wez-pain-control](https://github.com/sei40kr/wez-pain-control?tab=readme-ov-file) ⭐ 9 | 🐛 0 | 🌐 Lua | 📅 2023-11-21 - Pane control keybindings like tmux-pain-control.
* [selectnull/pinned-tabs.wezterm](https://github.com/selectnull/pinned-tabs.wezterm) ⭐ 3 | 🐛 0 | 🌐 Lua | 📅 2025-08-16 - Lets you assign a key binding to a specific tab.

## Media

* [xarvex/presentation.wez](https://github.com/xarvex/presentation.wez) ⭐ 17 | 🐛 0 | 🌐 Lua | 📅 2024-09-12 - Rather simple presentation mode toggle.

## Neovim

* [mrjones2014/smart-splits.nvim](https://github.com/mrjones2014/smart-splits.nvim) ⭐ 1,555 | 🐛 13 | 🌐 Lua | 📅 2026-02-13 - Provides an addon for seamless pane navigation between Neovim and the WezTerm MUX.
* [winter-again/wezterm-config.nvim](https://github.com/winter-again/wezterm-config.nvim) ⭐ 71 | 🐛 2 | 🌐 Lua | 📅 2025-08-27 - Interact with the WezTerm configuration directly from Neovim.

## Panes

* [ChrisGVE/pivot\_panes.wezterm](https://github.com/ChrisGVE/pivot_panes.wezterm) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2025-04-15 - Toggle pane orientation between horizontal and vertical splits.
* [bad-noodles/stack.wez](https://github.com/bad-noodles/stack.wez) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2025-11-23 - Stacked pane mode, work with multiple panes but see only one at a time.

## Session

* [MLFlexer/resurrect.wezterm](https://github.com/MLFlexer/resurrect.wezterm) ⭐ 271 | 🐛 34 | 🌐 Lua | 📅 2025-07-04 - Save and restore the state of windows, tabs and panes.
* [MLFlexer/smart\_workspace\_switcher.wezterm](https://github.com/MLFlexer/smart_workspace_switcher.wezterm) ⭐ 180 | 🐛 2 | 🌐 Lua | 📅 2025-06-30 - Switch between workspaces with fuzzy finding and `zoxide`.
* [mikkasendke/sessionizer.wezterm](https://github.com/mikkasendke/sessionizer.wezterm) ⭐ 83 | 🐛 1 | 🌐 Lua | 📅 2025-07-05 - Opening Git repositories as their own WezTerm workspaces using `fd`.
* [DavidRR-F/quick\_domains.wezterm](https://github.com/DavidRR-F/quick_domains.wezterm) ⭐ 27 | 🐛 4 | 🌐 Lua | 📅 2026-02-01 - Faster way to search and attach to (SSH) domains.
* [vieitesss/workspacesionizer.wezterm](https://github.com/vieitesss/workspacesionizer.wezterm) ⭐ 16 | 🐛 0 | 🌐 Lua | 📅 2025-07-07 - Blazingly fast workspace chooser inspired by `tmux-sessionizer`.
* [abidibo/wezterm-sessions](https://github.com/abidibo/wezterm-sessions) ⭐ 12 | 🐛 1 | 🌐 Lua | 📅 2026-01-20 - Save and restore sessions.
* [isseii10/workspace-picker.wezterm](https://github.com/isseii10/workspace-picker.wezterm) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2026-01-11 - Workspace switcher with `zoxide` integration.
* [JuanraCM/wsinit.wezterm](https://github.com/JuanraCM/wsinit.wezterm) ⭐ 3 | 🐛 0 | 🌐 Lua | 📅 2025-11-14 - A simple and flexible way to manage and initialize workspace configurations.
* [srackham/tabsets.wezterm](https://github.com/srackham/tabsets.wezterm) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2025-12-27 - Load, save, rename and delete named sets of tabs.

## Tab bar

* [michaelbrusegard/tabline.wez](https://github.com/michaelbrusegard/tabline.wez) ⭐ 264 | 🐛 5 | 🌐 Lua | 📅 2026-02-13 - A versatile and easy to use retro tab bar with the `lualine.nvim` configuration format.
* [adriankarlen/bar.wezterm](https://github.com/adriankarlen/bar.wezterm) ⭐ 204 | 🐛 5 | 🌐 Lua | 📅 2026-01-19 - A configurable tab bar with batteries included.
* [yriveiro/wezterm-tabs](https://github.com/yriveiro/wezterm-tabs) ⭐ 22 | 🐛 1 | 🌐 Lua | 📅 2025-01-01 - Configurable tabs for the retro tab bar.
* [yriveiro/wezterm-status](https://github.com/yriveiro/wezterm-status) ⭐ 21 | 🐛 0 | 🌐 Lua | 📅 2025-02-23 - Configurable status for the retro tab bar.
* [rootiest/battery.wez](https://github.com/rootiest/battery.wez) ⭐ 8 | 🐛 0 | 🌐 Lua | 📅 2024-10-07 - A colorful and fancy battery component for the retro tab bar.

## Themes

* [neapsix/wezterm](https://github.com/neapsix/wezterm) ⭐ 69 | 🐛 0 | 🌐 Lua | 📅 2024-05-11 - Rosé Pine theme, all natural pine, faux fur and a bit of soho vibes.
* [koh-sh/wezterm-theme-rotator](https://github.com/koh-sh/wezterm-theme-rotator) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2025-03-23 - Cycle through built-in themes using keyboard shortcuts.

## Utility

* [zsh-sage/toggle\_terminal.wez](https://github.com/zsh-sage/toggle_terminal.wez) ⭐ 23 | 🐛 1 | 🌐 Lua | 📅 2025-10-22 - An easy-to-use toggleable terminal window.
* [ChrisGVE/listeners.wezterm](https://github.com/ChrisGVE/listeners.wezterm) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2025-04-01 - Enables enhanced event listener capabilities with persistent state management.
* [ChrisGVE/lib.wezterm](https://github.com/ChrisGVE/lib.wezterm) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2025-04-15 - A library of common utility functions for plugin developers.
* [quickselect.wezterm](https://github.com/quantonganh/quickselect.wezterm) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2025-12-13 - Jump to the build error by opening them in Helix.
* [ChrisGVE/dev.wezterm](https://github.com/ChrisGVE/dev.wezterm) ⭐ 6 | 🐛 1 | 🌐 Lua | 📅 2025-12-01 - Location resolver for development and deployment of a plugin.
* [aureolebigben/wezterm-cmd-sender](https://github.com/aureolebigben/wezterm-cmd-sender) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2024-09-24 - Send commands to multiple panes.
* [btrachey/wezterm-replay](https://github.com/btrachey/wezterm-replay) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2025-09-18 - Parse command output and get URLs, shell commands, etc. pasted into your next prompt.
* [lilaqua/tunicodes](https://gitlab.com/lilaqua/tunicodes) - Insert Unicode characters via their codepoints.
