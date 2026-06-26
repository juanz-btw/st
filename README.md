Tiny opsec st patched terminal with another colo scheme and font 

## Installation

Build and install from source:

```bash id="g1m8s9"
git clone https://github.com/juanz-btw/st.git ~/st-patched

sudo pacman -S base-devel pkgconf fontconfig freetype2

cd ~/st-patched && sudo make clean install
