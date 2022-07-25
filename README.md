# Lazygit Configuration

All necessary Configurations to make lazygit a worthy replacement for GitHub Desktop (my current daily driver).

## Installation

```bash
brew install lazygit
```

## Usage

When in your repo directory

```bash
lazygit
```

## Keybindings

The bottom panel gives you basic navigation hints.

For help within each panel, use <kbd>?</kbd> this will open all possible commands for the current panel.

- Undo with <kbd>z</kbd>

- Redo with <kbd>CTRL</kbd> <kbd>z</kbd>

## Configuration

### Config Location

- Linux: `~/.config/lazygit/config.yml`
- MacOS: `~/Library/Application Support/lazygit/config.yml`
- Windows: `%APPDATA%\lazygit\config.yml`

### Changing default editor to Neovim from Vim

Add the following properties to your `config.yml`

```yml
os:
	editCommand: 'nvim'
```

