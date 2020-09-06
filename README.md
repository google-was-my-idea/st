# An Expert Noob build of ST - The suckless/simple terminal
Literally the best terminal i have ever used having an awesome unicode(🤣🙂😈👋) support.

## Out of the box support for 
- **Emoji and special character.** (its really cool to have emoji in terminal💀👹👽)
- **Transparency.**
- **Scrollback.**
- **Cursor Blinking.**
- **Gruvbox Color Scheme.**

## Steps before installation.
- Replace libxft package with libxft-bgra for BGRA glyphs and scaling support(emoji).
  You can install libxft-bgra-git from aur using aur helper
  or you can also make it on your own.
``````
yay -S libxft-bgra-git
``````
- Install fonts for emoji support.
``````
sudo pacman -S ttf-joypixels
``````
> or you can also install any other emoji font.

## Installation

- Clone the repo
````
git clone https://github.com/echo-rahul/st.git 
cd st
sudo make install
````

