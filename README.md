来自Github@Optixal  
原项目地址:https://github.com/Optixal/neovim-init.vim
### 截图:

### 安装:
```sh
apt install git wget nodejs neovim python3 clang python3 curl bat ripgrep silversearcher-ag
git clone https://github.com/Moe-hacker/termux-neovim
cd termux-neovim
mkdir -p ~/.config/nvim
cp init.vim ~/.config/nvim/
curl -fLo /data/data/com.termux/files/home/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
pip install wheel yapf jedi doq pynvim
```
打开neovim，报错直接忽略，输入:  
```sh
:PlugInstall
```
最后，neovim中使用:CocInstall安装想要的语言的自动补全功能。
