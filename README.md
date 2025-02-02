[//]: # (note for me - Linux/Unix Desktops > Desktop Themes > KDE > KDE Plasma > Plasma 6 splashscreen)

<p align="center">
  <a href="https://www.pling.com/p/2135195/">
    <img alt="kuro the cat" src="a2n.kuro/contents/splash/images/cat.gif" width="220"/>
  </a>
</p>
<h1 align="center">Kuro - Plymouth theme </h1>

## Description

Boot your pc with Kuro the cat

### history
Plymouth theme inspired by https://github.com/bouteillerAlan/kuro

# Installation
- Install plymouth on your distro by following guide written on your distro's wiki page or search on the internet. Do follow each and every steps properly ▼
  
  [Arch](https://wiki.archlinux.org/title/Plymouth)  [Debian](https://wiki.debian.org/plymouth)  [Ubuntu](https://wiki.ubuntu.com/Plymouth) [Linux-Mint](https://community.linuxmint.com/tutorial/view/646)  [Nix-OS](https://wiki.nixos.org/w/index.php?title=Plymouth&mobileaction=toggle_view_desktop)  [Gentoo](https://wiki.gentoo.org/wiki/Plymouth)  [EndeavourOS](https://forum.endeavouros.com/t/guide-how-to-install-and-use-plymouth/51363)  [Fedora](https://discussion.fedoraproject.org/t/enable-plymouth-startup/70079)  [MX-Linux](https://mxlinux.org/wiki/system/add-plymouth-to-mx-linux/)  [Manjaro](https://wiki.manjaro.org/index.php/Plymouth)  [openSUSE](https://en.opensuse.org/openSUSE:Plymouth)   



- After installation make sure that you have a themes folder inside /usr/share/plymouth/ if not then create one
by ▼ 
```bash
sudo mkdir /usr/share/plymouth/themes/
```

- Clone this repository if you want all the themes at once else if you want any individual theme then download it from release section
```bash 
git clone https://github.com/timscreep/kuro-plymouth.git
```

- After cloning or downloading your desired theme simply copy and paste your desired Theme to
```bash
/usr/share/plymouth/themes/
```

- Now just set your desired theme as default Plymouth theme and make sure to rebuild `initrd` for that just use command given below ▼
```bash  
sudo plymouth-set-default-theme kuro-plymouth -R 
```


