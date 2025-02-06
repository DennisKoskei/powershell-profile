# My Custom PowerShell Profile

## Overview

This is my custom PowerShell profile designed to enhance the command-line experience with useful functions, aliases, and automation scripts. The profile includes system utilities, networking tools, quality-of-life enhancements, and PowerShell appearance customizations.

---

## Features

### System Enhancements

- **Automatic PowerShell Update**: Checks for and updates PowerShell if a newer version is available.
- **Admin Status Detection**: Changes the command prompt to reflect admin privileges.
- **Cache Clearing**: Quickly clears system temp files, prefetch data, and browser cache.

### Command Aliases & Functions

- **Unix-like Aliases**:
  - `su` → Run command as admin
  - `ll` → List files with details
  - `la` → List all files including hidden ones
  - `df` → Show disk space usage
  - `which <cmd>` → Find location of a command
- **File & Directory Management**:
  - `mkcd <dir>` → Create and enter a new directory
  - `nf <file>` → Create a new file
  - `trash <file>` → Move file to recycle bin
- **Quick Navigation**:
  - `docs` → Go to Documents folder
  - `dtop` → Go to Desktop
  - `down` → Go to Downloads
  - `home` → Go to Home directory
- **Git Shortcuts**:
  - `gs` → Git status
  - `ga` → Git add all
  - `gc "msg"` → Git commit with message
  - `gp` → Git push
  - `lazyg "msg"` → Git add, commit, and push
- **Networking Tools**:
  - `Get-PubIP` → Get public IP address
  - `flushdns` → Clear DNS cache
- **Clipboard Utilities**:
  - `cpy <text>` → Copy text to clipboard
  - `pst` → Paste from clipboard
- **Neovim Integration**:
  - `v <file>` → Open file with Neovim
  - `v <dir>` → Open directory in Neovim

### PowerShell Customization

- Uses **Oh My Posh** for an improved terminal prompt.
- Automatically detects and sets the preferred text editor.

## Installation

1. Clone or download this profile script.
2. Place it in your PowerShell profile directory (typically `$PROFILE.CurrentUserAllHosts`).
3. Restart PowerShell to apply changes.

## Usage

- The profile loads automatically when PowerShell starts.
- Run `reload-profile` to reload without restarting.
- Use `Edit-Profile` (`ep`) to quickly open and modify the profile.

## Future Improvements

- Add key bindings for quick project navigation.
- Improve error handling in functions.

---

This profile is a work in progress and can be customized further based on user needs. Contributions and suggestions are welcome!
