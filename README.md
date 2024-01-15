From Github@Optixal  
[neovim-init.vim](https://github.com/Optixal/neovim-init.vim)
### Screenshot:
![](https://github.com/Moe-sushi/termux-neovim/raw/main/screenshot-neovim.jpg)
### Installation:   
```sh
apt install git wget nodejs neovim python3 clang python3 curl bat ripgrep silversearcher-ag
git clone https://github.com/Moe-sushi/termux-neovim
cd termux-neovim
mkdir -p ~/.config/nvim
cp init.vim ~/.config/nvim/
curl -fLo /data/data/com.termux/files/home/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
pip install wheel yapf jedi doq pynvim
```
Open neovim, and then execute:
```sh
:PlugInstall
```
Finally, use :CocInstall to install extension of coc.nvim.
