# pretty-terminator

- [Intro](#intro)
- [What's Included?](#whats-included)
- [Installation Instructions](#installation-instructions)
- [Credits](#credits)

##Intro
> Easy to use Terminator terminal color schemes.

This project is just a Terminator related part extracted from [iTerm Color Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes) repository.

All of schemes are concatenated into one file ready to paste into Terminator configuration. No need to add them one by one :wink:.

##What's Included?
Take a look at [Schemes List :page_facing_up:](SchemesList.md).

##Installation Instructions
To make you Terminator prettier copy [PrettyTerminator.ini](PrettyTerminator.ini) content and paste it into `[profiles]` section of configuration file located in: `~/.config/terminator/config`.

Your configuration file should look like this:
```ini
[global_config]
  inactive_color_offset = 0.69
  title_hide_sizetext = True
  window_state = maximise
[keybindings]
[layouts]
  [[default]]
    [[[child1]]]
      parent = window0
      profile = default
      type = Terminal
    [[[window0]]]
      parent = ""
      type = Window
[plugins]
[profiles]
  [[default]]
    background_color = "#300a24"
    background_image = None
    font = Monospace 11
    foreground_color = "#ffffff"
    show_titlebar = False
    use_system_font = False
; Paste PrettyTerminator config here.
  [[3024 Day]]
    palette = "#090300:#db2d20:#01a252:#fded02:#01a0e4:#a16a94:#b5e4f4:#a5a2a2:#5c5855:#e8bbd0:#3a3432:#4a4543:#807d7c:#d6d5d4:#cdab53:#f7f7f7"
    background_color = "#f7f7f7"
    cursor_color = "#4a4543"
    foreground_color = "#4a4543"
    background_image = None
  [[3024 Night]]
    palette = "#090300:#db2d20:#01a252:#fded02:#01a0e4:#a16a94:#b5e4f4:#a5a2a2:#5c5855:#e8bbd0:#3a3432:#4a4543:#807d7c:#d6d5d4:#cdab53:#f7f7f7"
    ...
```
After restarting Terminator you should be able to choose your favourite scheme. All of them can be selected from the terminals context menu under "Profiles" position.

See the Terminator documentation if you want to make further customizations.

##Credits
Big thanks to **[Mark Badolato](https://github.com/mbadolato)** for creating awesome **[iTerm2 Color Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes)** project!
