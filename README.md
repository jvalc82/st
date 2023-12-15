## jvalc's build of st

## Usage
Get more information about the usage of my build, including useful keybindings
by executing `man st` in your terminal.

## Used patches from suckless project
- alpha + focus:                        Add support for window transparency and change focus levels between foreground and background windows
- anysize:                              Resize st to any pixel size
- fix-keyboard-input:                   Allow client to use all key combinations found in GUI's
- font2:                                Allows to add more spare fonts to client
- scrollback + mouse + altscreen:       Add scrollback funcionality
- w3m:                                  Support w3m images
- xresources:                           Add support for configuration though Xresources

## Installation 
- `git clone https://gitlab.com/jvalc82/st.git`
- `cd st`
- `make`
- `sudo make install`

## Future steps
All the code can be expanded from source. Also, to change some of the configurations
you need edit the "config.h", do not edit "config.def.h".

