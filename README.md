# neovim-nvchad

- First install neovim, currently nvchad needs neovim 0.9.0.
- Download using: wget htps://github.com/neovim/neovim/releases/download/v0.9.0/nvim.appimage
- We need to change permissions: chmod u+x nvim.appimage
- Setting path so that we can open neovim using nvim commend: 
  - sudo ln -s ~/nvim.appimage /usr/bin/nvim
  - alias nvim="~/nvim.appimage"
- nvim on terminal and you are good to go :)

## Uninstalling neovim
- `rm -rf ~/.config/nvim`
- `rm -rf ~/.local/share/nvim`
