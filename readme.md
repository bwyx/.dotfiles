# install yay!!@!#w

## authorization & keyring

`yay -S sudo seahorse`

## shboom

`yay -S zsh zsh-completions zsh-syntax-highlighting zsh-autosuggestions fastfetch`

<https://dev.to/zeromeroz/setting-up-zsh-and-oh-my-zhs-with-autocomplete-plugins-1nml>

### DE

`yay -S sway swaybg swaylock swayidle waybar sway-launcher-desktop mako nwg-look font-manager`

## code

`yay -S visual-studio-code-bin`

### VSCode Setting

`ln -s ~/.config/vscode.json ~/.config/Code/User/settings.json`

### GTK

Theme : <https://github.com/TheGreatMcPain/gruvbox-material-gtk>

### Thunar

`yay -S thunar tumbler thunar-volman thunar-archive-plugin gvfs gvfs-smb sshfs catfish file-roller`

## Fonts

Create symlink from `~/fonts/xxx`.

`ln -s ~/fonts/Iosevka ~/.local/share/fonts`

Set GTK fonts
`gsettings set org.gnome.desktop.interface font-name "Iosevka Term Curly 9"`

### Apple Emoji

Download .ttf : <https://github.com/samuelngs/apple-emoji-ttf/releases>

`ln -s ~/fonts/AppleEmoji ~/.local/share/fonts`

#### Utilities

`yay -S wget`

#### Screenshots & Screen Record

`yay -S grim slurp wl-clipboard jq wf-recorder`

### Sound System

`https://github.com/mikeroyal/PipeWire-Guide#Installing-PipeWire-on-Arch-Linux`

`yay -S pipewire pipewire-alsa pipewire-pulse pipewire-jack wireplumber pavucontrol`