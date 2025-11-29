# KAngel Fastfetch

![Fastfetch screenshot with KAngel like logo from Needy Streamer Overload](./images/0001.png)

# INSTALLATION

To install the fastfetch config, use:

```bash
git clone https://github.com/Vapor55/KAngel-Fastfetch-Dotfiles.git ~/.config/fastfetch
```

> [!NOTE]
> _To use images in `*.png` extension, use:

```bash
sudo pacman -S imagemagick
```

or you use NixOS in configuration.nix:

```nix
{

  environment.systemPackages = with pkgs; [
    imagemagick
  ];

}
```
