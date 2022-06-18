# sddm Graphite-nord Theme

> This repository is a fork of the [Graphite-kde-theme](https://github.com/vinceliuice/Graphite-kde-theme).

## Installation on ArchLinux system

Install the `plasma-framework`.

```bash
sudo pacman -Sy plasma-framework
```

Copy the theme.

```bash
sudo cp -r Graphite-nord /usr/share/sddm/themes/
```

Change the `sddm` theme.

```bash
sudo nano /etc/sddm.conf.d/theme.conf
```

```conf
[Theme]
Current=Graphite-nord
```
