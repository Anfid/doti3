# i3-gaps config and scripts

## Keybindings
| Key               | Function                                                                   |
|-------------------|----------------------------------------------------------------------------|
| Meta+Enter        | Open new terminal window                                                   |
| Meta+Q            | Close focused window                                                       |
| Meta+\<direction> | Focus window to the \<direction> of the focused one                        |
| Meta+Shift+\<direction> | Move focused window to the \<direction>                              |
| Meta+Shift+\<n>   | Move focused window to workspace #\<n>                                     |
| Meta+\<n>         | Focus workspace #\<n>                                                      |
| Meta+Space        | Toggle floating window focus                                               |
| Meta+W > D        | Choose default layout                                                      |
| Meta+W > T        | Choose tab layout                                                          |
| Meta+W > S        | Choose stack layout                                                        |
| Meta+W > Space    | Toggle window floating                                                     |
| Meta+W > G        | Enable gaps                                                                |
| Meta+W > E        | Disable gaps (mnemonic - efficient layout)                                 |
| Meta+W > M        | Enter move mode                                                            |
| Meta+W > R        | Enter resize mode                                                          |
| Meta+G > I        | Enter inner gaps mode                                                      |
| Meta+G > O        | Enter outer gaps mode                                                      |
| Meta+E            | Open file explorer (ranger by default)                                     |
| Meta+X            | Execute shell command. Can also be used to run applications. Utilizes rofi |
| Meta+S            | Select window or run ssh. Very likely to be changed                        |
| Ctrl+Alt+L        | Lock screen. Enter password to unlock                                      |

Where:
* `+` - Press keys simultaneously
* `>` - Press keys consequently
* `Meta` - aka Windows, Super etc.
* `<n>` - number from 0 to 9
* `<direction>` - vim-like direction key. Arrow keys also work
  h - left
  j - down
  k - up
  l - right

In move mode press `<direction>` to move floating window in corresponding direction. Press `Shift+<direction>` to move faster. Resize mode can be accessed by `R`.
In resize mode press `J` to make window bigger and `K` to make window smaller vertically. Press `L` to make window bigger and `H` to make window smaller horizontally. Press `Shift+<direction>` to resize faster. Move mode can be accessed by `M`.
In gaps mode press `J` to increase gaps and `K` to decrease them. Add `Shift` to only change local gaps. Outer gaps mode can be accessed from Inner gaps by `O`, and Inner gaps from Outer gaps by `I`
All modes can be escaped with `Q`, `Esc` or `Enter`.


