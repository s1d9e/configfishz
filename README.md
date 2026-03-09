# Athena Fish Theme

A **neon green / matrix-cyberpunk** inspired theme for the **Fish shell**.  
It features a clean multi-line prompt, integrated Git status, custom success/error symbols (λ / ✗), full path display, and a cool ASCII art greeting with "ATHENA OS — ACCESS GRANTED".

## Features

- **Two-line prompt** for better readability:
  - Top line: user@host + full working directory + Git info
  - Bottom line: λ (success) or ✗ (error)
- **Neon green color scheme** (matrix-style) with customizable highlights
- **Git integration** via built-in `__fish_git_prompt` (shows branch, dirty state, ahead/behind)
- **Full path** (no truncation) – perfect for deep project structures
- **Custom greeting** with large ASCII art + welcome message
- Lightweight – no external dependencies or plugin managers required
- Works great in modern terminals (kitty, Alacritty, WezTerm, etc.)

Example prompt:
- ┌─[user@hostname] ~/projects/athena-fish-theme [main✗↑1]
- └─λ

## How To Install 
Manual Install

Clone the repo:Bashgit clone https://github.com/YOUR_USERNAME/athena-fish-theme.git
cd athena-fish-theme
Copy the config:Bashcp config.fish ~/.config/fish/config.fish
Reload Fish:fishsource ~/.config/fish/config.fish
# or just open a new terminal

Backup first (optional but smart):
fish[ -f ~/.config/fish/config.fish ] && mv ~/.config/fish/config.fish ~/.config/fish/config.fish.bak
Customization
Edit ~/.config/fish/config.fish to tweak:
fish# Main colors (hex without #)
set fish_color_command 00ff41      # commands
set fish_color_quote   7fff00      # strings
set fish_color_error   ff2a6d      # errors
set fish_color_param   a3ffb5      # parameters

# Git extras (uncomment/add as needed)
set -g __fish_git_prompt_showdirtystate yes
set -g __fish_git_prompt_showstashstate yes
set -g __fish_git_prompt_showupstream informative
set -g __fish_git_prompt_char_stateseparator ' '

# Change symbols
# └─λ  →  └─❯   or  └─➜  etc.
Want more Git info? Check Fish docs: https://fishshell.com/docs/current/cmds/__fish_git_prompt.html

Compatibility

Fish ≥ 3.4 (tested on 3.6+ / 4.x)
Best with truecolor terminals (enable with export TERM=xterm-256color or better)
Works in tmux, but enable truecolor in tmux.conf if needed
No issues reported on Linux/macOS; Windows WSL should be fine too

#if you have any problem, dm me on discord : s1d9e

<img width="1915" height="1008" alt="image" src="https://github.com/user-attachments/assets/30b4b5d4-4441-42fc-81cd-ee358d44e1af" />

