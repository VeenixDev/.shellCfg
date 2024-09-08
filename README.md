# ZSH Configuration

This is a personal repository to versionise my terminal setup. everything in here can (and probably will) change over time.

## Installation

```
git clone --depth 1 -- https://github.com/VeenixDev/.shellCfg.git 
```

Add `source .shellCfg/.initzsh` to your .zshrc file.

After that put the links to the git repo of all the plugins you want into `.exports::ZSH\_PLUGINS`, after this run `installShellPlugins`.

Now your shell is fully setup.

## Plugin Manager

This configuration comes with a lightweight plugin manager that is written 100% in zsh.

To get a list of all possible commands run `zshPM help`
