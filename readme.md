# install yay!!@!#w

## authorization & keyring

`yay -S sudo gnome-keyring`

## shboom

`yay -S zsh zsh-completions fastfetch`

### DE

`yay -S sway swaybg swaylock swayidle waybar sway-launcher-desktop waybar mako nwg-look font-manager`

## code

`yay -S visual-studio-code-bin`

### VSCode Setting

`ln -s ~/.config/vscode.json ~/.config/Code/User/settings.json`

### GTK

Theme : <https://github.com/Fausto-Korpsvart/Gruvbox-GTK-Theme>

`yay -S gtk-engine-murrine`

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
