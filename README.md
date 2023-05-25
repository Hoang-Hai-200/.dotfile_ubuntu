# .dotfile_ubuntu
package ubuntu :
    Nvim
    Tmux
    lsd
        https://github.com/trapd00r/LS_COLORS#information-for-developers
    zsh => ohmyzsh => powerlevel10k
    ranger  #https://vitux.com/how-to-install-ranger-terminal-file-manager-on-linux/
            #https://github.com/ranger/ranger/issues/547
            ![image](https://github.com/Hoang-Hai-200/.dotfile_ubuntu/assets/64273754/946443dd-a6b5-44d8-badd-066f1c9bf2a1)

    bpytop  #https://blog.eldernode.com/install-bpytop-on-ubuntu-centos-debian/
    bottom
    Tree #https://installati.one/install-tree-ubuntu-22-04/
    


 ************************************************** Nvim
    ~/.config/nvim
├── autoload
│   └── plug.vim
├── init.vim
├── map.vim
├── plugged
│   ├── NeoSolarized
│   └── vista.vim
└── setting
    ├── airline.vim
    ├── effect.vim
    ├── nerdtree.vim
    └── vim_air_theme.vim
    
********************************* Tmux
    ~/.tmux.conf
    ~/.tmux.powerline.conf


install lsd :
    sudo dpkg -i lsd-musl_0.23.1_amd64.deb
    
    
    
install fzf :
    install fd (using npm)
    install fzf :
        - for OS using git
        - for vim
