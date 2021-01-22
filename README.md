This recipe is a fork of: https://aur.archlinux.org/packages/kicad-git/

to allow us to build kicad to install into /opt/kicad599 and run in parallel
with existing KiCad installations.

To build:

- clone this repo
- `cd arch-aur-kicad-git`
- `makepkg`
- can inspect resulting package
- `sudo pacman -U kicad-git-5.99.0...zst`

Alternatively, you can download snapshots from:

http://bec-systems.com/kicad599/

and install them with `pacman -U`

While this seems to work, it has not been heavily tested, so I can't guarantee anything.
