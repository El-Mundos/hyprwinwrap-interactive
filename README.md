# hyprwinwrap-interactive

A fork of [hyprwinwrap](https://github.com/hyprwm/hyprland-plugins/tree/main/hyprwinwrap) with **toggleable interactive mode** - perfect for playing games as your wallpaper!

## What's different?

The original hyprwinwrap makes windows non-interactive (clicks pass through). This fork adds a dispatcher to toggle interactivity on/off with a keybind.

## Installation

```bash
hyprpm add https://github.com/YOURUSERNAME/hyprwinwrap-interactive
hyprpm enable hyprwinwrap-interactive
```

## Configuration

Add to your `hyprland.conf`:

```conf
# Basic hyprwinwrap config (same as original)
plugin:hyprwinwrap {
    class = your-window-class
}

# Keybind to toggle interactive mode
bind = SUPER, G, hyprwinwrap:toggle
```

## Usage

1. Launch your game/app that matches the configured class
2. It appears as your wallpaper (non-interactive by default)
3. Press your keybind (e.g., `Super+G`) to make it interactive
4. Play your game!
5. Press the keybind again to return to wallpaper mode

## Credits

- Original hyprwinwrap by [hyprwm](https://github.com/hyprwm)
- Interactive toggle by elmundos
