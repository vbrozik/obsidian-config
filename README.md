# Obsidian config

This is my Obsidian config managed with [chezmoi](https://www.chezmoi.io/).

## Installation

To install, run the following command:

``` bash
chezmoi init -C ~/.config/chezmoi-obsidian/chezmoi.toml vbrozik/obsidian-config
```

Then, apply the configuration:

``` bash
chezmoi -c ~/.config/chezmoi-obsidian/chezmoi.toml apply
```

Always make sure to use the `-c` flag to specify the correct configuration file when running `chezmoi` commands. I recommend creating an alias or function in your shell configuration to simplify this process.
