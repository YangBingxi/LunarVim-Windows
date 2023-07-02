# Windows10、Windows11 安装LunarVim
## 资料
- [LunarVim官网](https://www.lunarvim.org/docs/installation)
- [Vim小游戏](https://vim-adventures.com/)

## 环境准备
### NeoVim v0.9+
[link](https://github.com/neovim/neovim/releases/tag/stable) 

---

### git
[link](https://cli.github.com/) 
### make
[link](https://sourceforge.net/projects/mingw-w64/) 
Files->x86_64_win32-sjlj
下载后解压缩，将/bin目录添加到Path
将win32_make.exe改名为make.exe
### pip
安装python后，会自动安装
### python
[link](url) 
### npm
安装node.js后会自动安装
### node
[link](https://nodejs.org/en) 
### cargo
[link](https://www.rust-lang.org/tools/install) 

---

### PowerShell 7+
[link](https://learn.microsoft.com/en-us/powershell/scripting/whats-new/migrating-from-windows-powershell-51-to-powershell-7?view=powershell-7.2) 


## 安装
powershell执行：`pwsh -c "`$LV_BRANCH='release-1.3/neovim-0.9'; iwr https://raw.githubusercontent.com/LunarVim/LunarVim/release-1.3/neovim-0.9/utils/installer/install.ps1 -UseBasicParsing | iex"`
安装后的lvim在`user/.local/bin/lvim.ps1`
"# LunarVim-Windows" 

## 安装后
添加字体：
`mkdir -p ~/.local/share/fonts
cd ~/.local/share/fonts && curl -fLO https://github.com/ryanoasis/nerd-fonts/raw/HEAD/patched-fonts/DroidSansMono/DroidSansMNerdFont-Regular.otf`
