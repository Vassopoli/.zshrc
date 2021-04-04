# zshrc

Configuration used by me on zsh


## Dependencies
- [zsh](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)
- [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh)
- [spaceship-prompt](https://github.com/denysdovhan/spaceship-prompt)
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)

## Setting up

1. First of all, clone this repository

    ```sh
    git clone https://github.com/Vassopoli/zshrc.git
    ```

2. Now, enter the folder

    ```sh
    cd zshrc
    ```

3. And finally, create a hard link in your home folder. Note the `-f` flag that forces the link creation, overriding existing auto-generated `.zshrc`.

    ```sh
    ln -f ./.zshrc $HOME/.zshrc
    ```