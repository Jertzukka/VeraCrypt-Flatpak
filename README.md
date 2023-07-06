ONLY FOR DEVELOPMENT; THIS DOESN'T WORK PROPERLY, DON'T USE THIS.

Install necessary dependencies:
`flatpak install flathub org.gnome.Platform//43`
`flatpak install flathub org.gnome.Sdk//43`

Clone this repo and in the root, run:
`flatpak-builder --user --install build-dir fr.veracrypt.veracrypt_testing.yml`

The program should be installed, or can be launched via:
`flatpak run fr.veracrypt.veracrypt_testing`
