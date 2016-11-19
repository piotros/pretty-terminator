# pretty-terminator

- [Intro](#intro)
- [Installation Instructions](#installation-instructions)

##Intro
Easy to use Terminator terminal color schemes.

##Installation Instructions
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
; [[3024 Day]]
;   palette = "#090300:#db2d20:#01a252:#fded02:#01a0e4:#a16a94:#b5e4f4:#a5a2a2:#5c5855:#e8bbd0:#3a3432:#4a4543:#807d7c:#d6d5d4:#cdab53:#f7f7f7"
;   background_color = "#f7f7f7"
;   cursor_color = "#4a4543"
;   foreground_color = "#4a4543"
;   background_image = None
; [[3024 Night]]
;   palette = "#090300:#db2d20:#01a252:#fded02:#01a0e4:#a16a94:#b5e4f4:#a5a2a2:#5c5855:#e8bbd0:#3a3432:#4a4543:#807d7c:#d6d5d4:#cdab53:#f7f7f7"
;   ...
```
