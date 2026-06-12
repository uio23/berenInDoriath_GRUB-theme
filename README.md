# berenInDoriath_GRUB-theme
A Tolkien inspired GRUB2 theme with a gruvbox colour palette
## Demo
![demo](https://github.com/user-attachments/assets/0619d43e-f7b0-4079-8a74-30f421e5689d)
## Lore
Beren was a man from the Firs Age, who, with the elf princess of Doriath Lúthien, entered Angband and stole one of the three Silmarils, prised jewels over which the Noldor elves waged war on Morgoth, from his crown.
## Installation
1. Download and unzip the content of this repository into $prefix/themes/ (typically /boot/grub/themes).
2. Edit /etc/default/grub and set **GRUB_THEME** to this directory.<br>
E.g.
`GRUB_THEME="/boot/grub/themes/berenInDoriath"`
###### NOTE
The theme as it is includes icons for menu entries: arch, windows, settings and shutdown. To make sure they are displayed alongside the matching menu entries, please make sure that these menu entries are generated
with corresponding --class tags: arch, windows, settings and shutdown.[^1]
## Expanding
If you would like icons for other OSes or options, here is what I suggest:
1. Find the desired icon online.
2. Use an online png colour changer to change the icon's colour to #665c54 (that's bg3 in gruvbox dark mode).
3. Use an online png background remover to make the icon's background transparent.
4. Add the resulting png file to BerenInDoriath/icons on your system.
5. Make sure the icon's name matches the --class tag of the menu entry you want it to display for. [^1]
## Credits
* This theme was inspired by, and a result of heavy modification to [x4121's grub-gruvbox theme](https://github.com/x4121/grub-gruvbox).
* All 3 images displayed around the GRUB menu are drawings of J.R.R Tolkien and belong to the [Tolkien Estate](https://www.tolkienestate.com/).
* Colour modified Settings and Shutdown icons are from [Font Awesome](https://fontawesome.com).
* Colour modified Arch icon by [John Gardner](https://github.com/Alhadis) from [creazilla](https://creazilla.com/).
* Colour modified Windows icon by [logowiki](https://logowik.com).
* Colours used from theme [gruvbox](https://github.com/morhetz/gruvbox).

[^1]: Please look online or at the [GRUB Manual](https://www.gnu.org/software/grub/manual/grub/grub.html) for details/instructions on how to do this.
