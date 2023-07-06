**ONLY FOR DEVELOPMENT; THIS DOESN'T WORK PROPERLY, DON'T USE THIS.**


Install necessary dependencies:
```
flatpak install flathub org.gnome.Platform//43
flatpak install flathub org.gnome.Sdk//43
```
___
To build and install this locally, clone the repo and run:
```
flatpak-builder --user --install build-dir fr.veracrypt.veracrypt_testing.yml
```
The program should be installed, or can be launched via:
```
flatpak run fr.veracrypt.veracrypt_testing
```
___
To build into repo directory and create .flatpak file:
```
flatpak-builder --repo=repo build-dir fr.veracrypt.veracrypt_testing.yml
flatpak build-bundle repo veracrypt_testing.flatpak fr.veracrypt.veracrypt_testing
```
