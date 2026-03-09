# Athena Fish Theme

A **neon green / matrix-cyberpunk** inspired theme for the **Fish shell**.  
It features a clean multi-line prompt, integrated Git status, custom success/error symbols (λ / ✗), full path display, and a cool ASCII art greeting with "ATHENA OS — ACCESS GRANTED".

## Features

- **Two-line prompt** for better readability:
- **Top line**: user@host + full working directory + Git info
- **Bottom line**: λ (success) or ✗ (error)
- **Neon green color scheme** (matrix-style) with customizable highlights
- **Git integration** via built-in `__fish_git_prompt` (shows branch, dirty state, ahead/behind)
- **Full path** (no truncation) – perfect for deep project structures
- **Custom greeting** with large ASCII art + welcome message
- **Lightweight** – no external dependencies or plugin managers required
- Works great in modern terminals (kitty, Alacritty, WezTerm, etc.)

Example prompt:
- ┌─[user@hostname] ~/projects/athena-fish-theme [main✗↑1]
- └─λ
<img width="1915" height="1008" alt="image" src="https://github.com/user-attachments/assets/30b4b5d4-4441-42fc-81cd-ee358d44e1af" />

## Manual Install
 
Clone the repo:
```git clone https://github.com/YOUR_USERNAME/athena-fish-theme.git```
cd athena-fish-theme
cp config.fish ~/.config/fish/config.fish
source ~/.config/fish/config.fish
# or just open a new terminal

Backup first (optional but smart):
[ -f ~/.config/fish/config.fish ] && mv ~/.config/fish/config.fish ~/.config/fish/config.fish.bak

## Compatibility
Fish ≥ 3.4 (tested on 3.6+ / 4.x)
Best with truecolor terminals (enable with export TERM=xterm-256color or better)
Works in tmux, but enable truecolor in tmux.conf if needed
No issues reported on Linux/macOS; Windows WSL should be fine too

# my contact : 
**discord : s1d9e** 
**https://guns.lol/s1d9e** 
