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

## 🚀 General Commands

| Command | Usage | Description |
|---------|-------|-------------|
| `!h` | `!h` | Show help/keys reference |
| `clear` | `clear` | Clear terminal history |
| `refresh` | `refresh` | Force refresh the UI |
| `theme` | `theme` | Cycle to next color theme |
| `save` | `save` | Save dashboard snapshot to file |

## 🔄 Mode & Auto Commands

| Command | Usage | Description |
|---------|-------|-------------|
| `auto` | `auto` | Cycle auto mode (Off → Roblox → MuMu → LDPlayer → AutoDetect → Adaptive) |
| `stopauto` | `stopauto` | Stop auto mode immediately |

## 💾 Memory & Process Commands

| Command | Usage | Description |
|---------|-------|-------------|
| `alloc` | `alloc` | Apply memory limits to all detected Roblox/emulator processes |
| `killall` | `killall` | Kill all Roblox, MuMu, and LDPlayer processes |
| `!k <pid>` | `!k 1234` | Kill a specific Roblox process by PID |
| `!cpu <cores>` | `!cpu 2` | Set CPU cores per Roblox process (1-8). Use `!cpu` alone to show current value. |
| `setinterval <sec>` | `setinterval 10` | Set auto-detect interval (3-30 seconds) |

## 🌐 WebSocket Commands

| Command | Usage | Description |
|---------|-------|-------------|
| `ws on` | `ws on` | Start WebSocket server on port 1337 |
| `ws off` | `ws off` | Stop WebSocket server |

## 🎮 VRAM Command

| Command | Usage | Description |
|---------|-------|-------------|
| `vram` | `vram` | Clear GPU VRAM cache |

## ⚡ Volt Commands

| Command | Usage | Description |
|---------|-------|-------------|
| `voltopen` | `voltopen` | Launch Volt UI application |
| `voltclose` | `voltclose` | Close Volt UI process |
| `voltupdate` | `voltupdate` | Trigger Volt update (close + reopen with delay) |
| `voltstatus` | `voltstatus` | Show Volt running status and version |
| `voltversion` | `voltversion` | Show installed Volt version |
| `voltlogin` | `voltlogin` | Save Volt login credentials to config |
| `voltuser <user>` | `voltuser myuser` | Set Volt username |
| `voltpass <pass>` | `voltpass mypass` | Set Volt password |
| `voltversionpin <ver>` | `voltversionpin v1.2.3` | Pin a specific Volt version |

## 🖥️ Shell Command

| Command | Usage | Description |
|---------|-------|-------------|
| `shell <cmd>` | `shell dir` | Execute any Windows cmd.exe command and show output in terminal |

---

## 📝 Quick Examples

```bash
# Start auto-detection mode
auto

# Set CPU cores for Roblox processes
!cpu 4

# Kill all processes
killall

# Launch Volt
voltopen

# Execute system command
shell ipconfig
