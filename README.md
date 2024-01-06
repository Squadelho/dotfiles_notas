Dotfiles de Squadelho para UBUNTU 

 - Neovim



resolver o problema do git nas credenciais usando gh(depois de ter dado login): 
git config --global 'credential.https://github.com.helper' ''
git config --global --add 'credential.https://github.com.helper' '!gh auth git-credential'
