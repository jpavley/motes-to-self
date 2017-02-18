# macOS System Setup
john@pavley.com

## YADR

- The best vim,git,zsh plugins and the cleanest vimrc you've ever seen http://skwp.github.com/dotfiles

### Install and update

- Execute in the terminal: 
``` sh -c "`curl -fsSL https://raw.githubusercontent.com/skwp/dotfiles/master/install.sh `" ```
- run to update: cd to ~/.yadr and execute ``` rake update ```

### Cusomizations

- Update ~/.zsh.after/prompt.zsh

```
prompt pure
date
cal
echo "all systems nominal..."
```

## macOS Customizations

- System Preferences/Keyboard/Modifier Keys/Caps Lock Key: **Escape**
- System Preferences/Keyboard/Key Repeat: **Fast**
- System Preferences/Keyboard/Delay Until Repeat: **Short**

## Installed via Homebrew

### Shpotify - A commandline interface to Spotify

``` brew install shpotify ```

### Graphviz - graphviz.org

``` brew install graphviz ```

### Lynx - The text web browser - lynx.browser.org

``` brew install lynx ```

``` 
    ~/.lynxrc
    show_color=never
    vi_keys=on
```

### Pandoc - A universal document converter

``` brew install pandoc ```

