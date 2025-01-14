<h1 align="center">
  <img src="data/icons/io.github.mpobaschnig.Vaults.svg" alt="Vaults" width="128" height="128"/><br>
  Vaults
</h1>

<p align="center"><strong>Keep important files safe</strong></p>

<p align="center">
 <a href="https://flathub.org/apps/details/io.github.mpobaschnig.Vaults"><img width="200" alt="Download on Flathub" src="https://flathub.org/assets/badges/flathub-badge-en.png"/></a>
</p>

<p align="center">
  <img src="data/resources/screenshots/main.png" alt="Main Window"/>
</p>

Vaults lets you create encrypted vaults in which you can safely store files.
It currently uses [gocryptfs](https://github.com/rfjakob/gocryptfs) and [CryFS](https://github.com/cryfs/cryfs/) for encryption.  Please always keep a backup of your encrypted files.

## Dependencies

This version does not bundle [gocryptfs](https://github.com/rfjakob/gocryptfs) and [CryFS](https://github.com/cryfs/cryfs/) yet, so you need to install them on the host.

## How to build

The simplest way to build Vaults is using GNOME Builder:

- Click `Clone Repository...`
- Enter repository URL
- Press `Clone Project`
- Click run/build button or press `F5`
