# Basic, most common commands for neovim

## Modes

- **Esc** - back to command mode
- **i**- editing mode
- **:someComand** - enter command
- **:q** - quit
- **:wq** - write done changes and quit
- **:w** - write down changes

## Plugins

- **PluginInstall**
- **PluginUpdate**

## Editor

### Select text

- select text:
  - **v** - in command mode, select text
  - **V** - in command mode, select line
- cut out text:

  - **d** - cut out text

- copy text:

  - **y** - copy text
  - **"+y** - copies to the "usual" clipboard buffer
  - **"\*y** - copies to the X11 selection - you can paste from this buffer using middle click

- paste text:
  - **P** - paste text before the cursor
  - **p** - paste text after the cursor
  - **u** - in command mode, undo

### Manage screen

- **:term** - open terminal
  - screen navigation: **Ctrl+w+w**
  - **exit** - exit from termonal mode
  - **split** or **Ctrl+w+s** - split screen horizontally
  - **vsplit** or **Ctrl+w+v** - split screen vertically
  - **Ctrl+w+h** - move left screen
  - **Ctrl+w+l** - move right
  - **Ctrl+w+k** - move top
  - **Ctrl+w+j** - move bottom
- Change size of current screen:
  - **Ctrl+w++** - increase the height of the current window by one line
  - **Ctrl+w+-** - decrease the height of the current window by one line
  - **Ctrl+w+>** - increase the width of the current window by one column
  - **Ctrl+w+<** - decrease the width of the current window by one column
