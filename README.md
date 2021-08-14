
Change dir to .config/
Clone NVIM Config repo
ln -s nvim_config nvim

# download plug module
curl -fLo ~/.config/nvim/autoload/plug.vim --create-dirs \
https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

#open nvim
#execute ->   :PlugInstall
