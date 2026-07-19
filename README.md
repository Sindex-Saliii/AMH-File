# Alchemy Terminal Command Reference

A comprehensive terminal command system for managing Roblox processes, emulators, and Volt applications with advanced automation features.

## 📋 Table of Contents
- [General Commands](#general-commands)
- [Mode & Auto Commands](#mode--auto-commands)
- [Memory & Process Commands](#memory--process-commands)
- [WebSocket Commands](#websocket-commands)
- [VRAM Command](#vram-command)
- [Volt Commands](#volt-commands)
- [Shell Command](#shell-command)

---

## Terminal Commands

All commands typed in the in-app terminal (Ctrl+T to focus).

| Command | Description |
|---------|-------------|
| `!h` | Show help |
| `clear` | Clear terminal |
| `refresh` | Force UI refresh |
| `theme` | Cycle theme (8 themes) |
| `auto` | Cycle auto mode (Manual → Roblox → MuMu → LDPlayer → AutoDetect → Adaptive) |
| `stopauto` | Stop auto mode |
| `alloc` | Apply memory limits to all targets |
| `killall` | Kill all Roblox/MuMu/LDPlayer processes |
| `ws on` | Start WebSocket server (port 1337) |
| `ws off` | Stop WebSocket server |
| `vram` | Clear GPU VRAM cache |
| `save` | Save dashboard snapshot to file |
| `!bbasync` | Wipe BanAsync associations (registry, cookies, cache) in background |
| `!cpu <1-8>` | Set CPU cores per Roblox process |
| `!k <pid>` | Kill a Roblox process by PID |
| `setinterval <3-30>` | Set auto detect interval in seconds |
| `shell <cmd>` | Run a shell command and show output |
| `voltopen` | Open Volt UI |
| `voltclose` | Close Volt UI |
| `voltupdate` | Trigger Volt update |
| `voltstatus` | Show Volt running status & version |
| `voltversion` | Show Volt version |
| `voltlogin` | Save Volt login credentials |
| `voltuser <name>` | Set Volt username |
| `voltpass <pass>` | Set Volt password |
| `voltversionpin <ver>` | Pin Volt to a specific version |

## WebSocket Commands

Connect to `ws://localhost:1337`

| Command | Description |
|---------|-------------|
| `AUTH:<token>` | Authenticate (must match license token) |
| `GET_CLIENTS` | List all tracked processes |
| `GET_STATUS` | Get system status & config |
| `GET_PROCESS_DETAILS:<PID>` | Get process info |
| `KILL:<PID>` | Kill process by PID |
| `KILL_ALL` | Kill all targets |
| `ALLOCATE` | Apply memory limits |
| `CLEAR` | Clear system cache |
| `AUTO_ON` | Enable auto mode |
| `AUTO_OFF` | Disable auto mode |
| `SET_INTERVAL:<seconds>` | Set auto detect interval (3-30) |
| `PING` | Connection test |
| `EXIT` | Disconnect |
| `HELP` | Show available commands |

## Keybinds

| Key | Action |
|-----|--------|
| `F1` | Help |
| `F3` | Save snapshot |
| `F4` | Cycle theme |
| `F5` | Cycle auto mode |
| `F6` | Apply memory limits |
| `F7` | Toggle WebSocket |
| `F8` | Stop auto mode |
| `F11` | Clear VRAM |
| `Ctrl+T` | Toggle terminal focus |
| `Tab` | Switch sidebar/terminal focus |
| `↑/↓` | Navigate sidebar or scroll |
| `Q` | Quit |

