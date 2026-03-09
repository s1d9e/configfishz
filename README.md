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
┌─[user@hostname] ~/projects/athena-fish-theme [main✗↑1]
└─λ

