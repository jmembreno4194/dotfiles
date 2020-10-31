# Workstation Vimrc Config
*Supported systems:*
- Linux (Any distros based off of debian)
- Windows: Windows Subsystem for Linux (Ubuntu/Debian/Kali Linux)
Article on how to enable Windows Subsystem for Linux https://www.windowscentral.com/install-windows-subsystem-linux-windows-10

# Features/Keymappings
- F2 to Toggle NERDTree (`:NERDTreeToggle`)
- F3 to toggle line numbers (`:set invnumber`)
- F4 to quit without saving (`:q!`)
- F5 to open a split window (`:vsplit`)
- Tab to switch between split windows (CTRL+w+w)
- F6 to toggle between passive/active syntastic checker (`:SyntasticToggleMode`)
- F8 to compile/run C/CPP using Makefile and clear console
- F9 to compile/run languages and clear console
- F12 to source file (`:source %`)

# Supported F9 filetypes/languages
- C
- CPP
- HTML
- Java
- Perl
- Python
- Shell

# Linux
You will need to install the plugin managers to get the plugins installed and working:
### Vim-Plug
`curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim`

### Vundle
`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

After installing the plugin managers, you will need to access the vimrc and run the following commands in vim:
- *Vim-Plug:* `:PlugInstall`
- *Vundle:* `:PluginInstall`



