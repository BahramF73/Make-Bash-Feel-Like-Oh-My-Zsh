# Make Bash Feel Like Oh My Zsh
## Install [Starship](https://github.com/starship/starship)
### 1. Install Starship:  
```sh
curl -sS https://starship.rs/install.sh | sh
```
### 3. Enable Starship:  
```sh
echo 'eval "$(starship init bash)"' >> ~/.bashrc
# or for root user
# echo 'eval "$(starship init bash)"' | sudo tee -a /root/.bashrc
```
### 4. Install [Nerd Font](https://www.nerdfonts.com/):  
for example run this to install [0xProto Font](https://github.com/0xType/0xProto):
```sh
curl -LO https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/0xProto.zip
unzip 0xProto.zip -d 0xProto
mkdir -p "$HOME/.local/share/fonts" && cp *.ttf "$HOME/.local/share/fonts/" && fc-cache -fv

```
