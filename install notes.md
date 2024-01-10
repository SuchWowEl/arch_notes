# Notes
- check first if to disk/boot uses uefi or bios
- When partitioning, use `cfdisk /dev/smth`
- `pacman -Sy vim` to check if installation doesn't fail, else do `pacman-key --refresh-keys`
  - `pacman-key --init && pacman-key --populate`
- grub-install --target=x86_64-efi --efi-directory=/boot --bootloader-id=GRUB
- user should be `zakaii`
- try to install firefox
  - try `sudo pacman -Syu` or `sudo pacman -Su` if it doesn't work
