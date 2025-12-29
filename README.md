# psscope

psscope is a lightweight process inspection and observation tool for Linux systems. Similar to Windows Process Explorer, but designed for Linux terminal environments.

It provides real-time visibility into process state, CPU usage, memory consumption, threads, file descriptors, and more through a terminal-based user interface (TUI).

## Features

- Real-time process monitoring with 1-second refresh
- Process tree view and list view
- 9 detail tabs: Overview, Threads, Files, Memory, Libraries, Environment, Signals, Locks, Resources
- Multiple sort options (CPU, Memory, PID, Name, User, Time, State, etc.)
- Process dump generation and analysis
- Bookmark functionality
- Dark and Mono themes
- Keyboard-driven navigation

## Supported Platforms

- Linux x86_64 (amd64)

## Download

See the [Releases](../../releases) page for binary downloads.

> **Note:** The automatically generated "Source code" archives do not contain the actual source code. This project is distributed as **binary-only**. Please download the executable files from the Assets section.

## Installation

```bash
# Download the binary
chmod +x psscope
./psscope
```

For system-wide installation:
```bash
sudo install -m 755 psscope /usr/local/bin/
```

## Keyboard Shortcuts

### Navigation
| Key | Action |
|-----|--------|
| j/k/↑/↓ | Navigate process list |
| PgUp/PgDn | Page navigation |
| Home/End | First/last process |

### Sorting
| Key | Action |
|-----|--------|
| c | Sort by CPU |
| m | Sort by memory |
| p | Sort by PID |
| n | Sort by name |

### View & Actions
| Key | Action |
|-----|--------|
| t | Toggle tree/list view |
| 1-9 | Switch detail tabs |
| b | Bookmark process |
| F5 | Refresh |
| F9 | Terminate process |
| ?/F1 | Help |
| q | Quit |

## Detail Tabs

1. **Overview** - General process information
2. **Threads** - Thread list and CPU usage
3. **Files** - Open file descriptors
4. **Memory** - Memory maps and usage
5. **Libraries** - Loaded shared libraries
6. **Environment** - Environment variables
7. **Signals** - Signal masks
8. **Locks** - File locks held
9. **Resources** - Resource limits (ulimits)

## License

Free for personal and internal use. **Commercial use requires a license.**

See [LICENSE.txt](LICENSE.txt) for details.

## Security

See [SECURITY.md](SECURITY.md) for security policy and vulnerability reporting.
