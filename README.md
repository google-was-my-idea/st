# An Expert Noob build of ST - The suckless/simple terminal
- Literally the best terminal i have ever used having an awesome unicode(🤣🙂😈👋) support.
- Minimalist free from bloat.
- From suckless

## This build provide out of the box support for 
- **Emoji and special character.** (Yeah man emoji in terminal💀👹👽 it's really cool)
- **Transparency.**
- **Scrollback.**
- **Cursor Blinking.**
- **Gruvbox Color Scheme.** (A color scheme which just feels light on eyes)

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

- Clone the repo and install it.
````
git clone https://github.com/echo-rahul/st.git 
cd st
sudo make install
````


## Details of the patches applied
- alpha
- blinking cursor
- desktopentry
- gruvbox
- font2
- scrollback

## You can also build your own st
> check out more patches at [suckless](https://st.suckless.org/)

## More gruvbox color scheme
> [gruvbox](https://github.com/morhetz/gruvbox)

Thanks and Enjoy this build !
