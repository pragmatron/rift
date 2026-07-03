# Wayne Rift Hotkeys

Current build:
- repo: `~/Documents/Codex/2026-05-16/comparison-of-different-modern-window-managers/rift`
- branch: `wayne/scrolling-niri-fixes`
- binary: `~/.local/bin/rift`
- cli: `~/.local/bin/rift-cli`
- config: `~/.config/rift/config.toml`

Core:
- `Alt+H/J/K/L`: focus left/down/up/right
- `Alt+Shift+H/J/K/L`: move window/node left/down/up/right
- `Alt+Ctrl+H/L`: move whole scrolling column left/right
- `Alt+0/1/2/3`: switch workspace
- `Alt+Shift+0/1/2/3`: move window to workspace
- `Alt+Tab`: previous workspace

Scrolling:
- `Alt+C`: center selected column
- `Alt+Shift+C`: snap strip
- `Alt+Ctrl+Left/Right`: scroll strip left/right
- `Alt+Shift+Equal/Minus`: grow/shrink selected window

Layouts:
- `Alt+Ctrl+1`: scrolling
- `Alt+Ctrl+2`: stack
- `Alt+Ctrl+3`: BSP
- `Alt+Ctrl+4`: master-stack

Groups/Stacks:
- `Alt+Shift+Left/Right/Up/Down`: join window with neighbor
- `Alt+Comma`: toggle stack
- `Alt+Slash`: toggle orientation
- `Alt+Ctrl+E`: unjoin windows

Float/Fullscreen:
- `Alt+Shift+Space`: toggle focused window floating
- `Alt+F`: fullscreen
- `Alt+Shift+F`: fullscreen within gaps

Rift UI:
- `Alt+Ctrl+M`: Rift Mission Control all workspaces
- `Alt+Ctrl+Shift+M`: Rift Mission Control current workspace
- `Alt+Ctrl+Z`: toggle whether Rift manages current macOS Space

Service:
- `rift service start`
- `rift service stop`
- `rift service restart`
- `rift service uninstall`

Queries:
- `rift-cli query displays`
- `rift-cli query workspaces`
- `rift-cli query windows`
- `rift-cli query layout`
