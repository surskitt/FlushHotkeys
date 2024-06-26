# FlushHotkeys
Some useful hotkeys for [Balatro](https://store.steampowered.com/app/2379780/Balatro). Requires [Steamodded](https://github.com/Steamopollys/Steamodded).

## Hotkeys
| Key | Use                              |
| :-: | -------------------------------- |
| `F` | Select cards with the same suit. |
| `D` | Select full houses, four of a kinds etc. |
| `S` | Invert selected cards. Tries to select "most discardable" cards. |

Pressing the hotkeys multiple times cycles through the options.
## Installation
Download the `FlushHotkeys.lua` file and then follow instructions from [here](https://github.com/Steamopollys/Steamodded?tab=readme-ov-file#how-to-install-a-mod).

## Scroll Wheel Mode
Use the `FlushHotkeys-scrollwheel.lua` file to enable using scroll wheel. This will **disable all other functionality** for the scroll wheel.

| Key | Use                              |
| :-: | -------------------------------- |
| `Wheel Down` | Select cards with the same suit. |
| `Wheel Up` | Select full houses, four of a kinds etc. |
| `Middle Mouse Button` | Invert selected cards. Tries to select "most discardable" cards.|

## Configuration
If you want to, for example change flush hotkey to `Q`, open the `FlushHotkeys.lua` file with notepad and change the
```lua
local flush_hotkey = "f"
```
line into:
```lua
local flush_hotkey = "q"
```

For mouse buttons, change `local mouse_flush_hotkey = 400` into `local mouse_flush_hotkey = 3` which sets the hotkey into Middle Mouse Button. If you have a custom 4th button change it to `4` etc. This does not unbind the corresponding keyboard hotkey.

## Contributing
Feature and pull requests are welcome.

## License

[MIT](https://choosealicense.com/licenses/mit/)