# sm64ex-mult
Multiplayer fork of [sm64pc/sm64ex](https://github.com/sm64pc/sm64ex). Currently an extreme WIP.

Feel free to report bugs and contribute, but remember, there must be **no upload of any copyrighted asset**.
Run `./extract_assets.py --clean && make clean` or `make distclean` to remove ROM-originated content.

## How to use
Player 1 is controlled by the keyboard, while Player 2 is controlled by a controller.  
Many interactions, such as menus, opening doors, and entering paintings, can be only performed by Player 1 currently.

## Building
**DO NOT BUILD WITH BETTERCAMERA=1**. BETTERCAMERA works by hijacks Player 2's controller, so Player 2 will not work with it enabled.  
For building instructions, please refer to [sm64ex's wiki](https://github.com/sm64pc/sm64ex/wiki). Build instructions should be the same.
