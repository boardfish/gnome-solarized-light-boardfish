# GNOME Solarized Light Theme

This is a theme that roughly sticks to [Solarized](https://ethanschoonover.com/solarized/) Light, a theme originally created by Ethan Schoonover, while also using my highlight color, `#069`. It's tested working on Ubuntu 19.04 and 19.10, but anything that shares its version of GNOME *should* be fine.

## Installation

Replace `/usr/share/gnome-shell/theme/gdm3.css` with the equivalent from this repository, then log out and back in again to see your changes.

If you've got a favorite color, a simple find-and-replace for #069 should do the trick. You can edit the file with `vim`. Type `:%s/#069/#00beef/g`, for example, and hit Enter. Then, enter `:w` followed by the Enter key to save.

You may also want to use [Oomox](https://github.com/themix-project/oomox) to create and apply solarised themes. Instructions for this will be added to the repository in due time.
