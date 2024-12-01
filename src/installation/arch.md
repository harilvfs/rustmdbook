# Arch Linux

[![linutil AUR Version](https://img.shields.io/aur/version/linutil?style=for-the-badge&label=%5BAUR%5D%20linutil&color=%23230567ff)](https://aur.archlinux.org/packages/linutil)

[![linutil-bin AUR Version](https://img.shields.io/aur/version/linutil-bin?style=for-the-badge&label=%5BAUR%5D%20linutil-bin&color=%23230567ff)](https://aur.archlinux.org/packages/linutil-bin)

### Linutil can be installed on [Arch Linux](https://archlinux.org) with three different [AUR](https://aur.archlinux.org) packages:

- `linutil` - Stable release compiled from source
- `linutil-bin` - Stable release pre-compiled
- `linutil-git` - Compiled from the last commit (not recommended)

### Package Build:

```bash
git clone https://aur.archlinux.org/<package>.git
cd <package>
makepkg -si
```

*Replace `<package>` with your preferred package.*

**If you use [yay](https://github.com/Jguer/yay), [paru](https://github.com/Morganamilo/paru) or any other [AUR Helper](https://wiki.archlinux.org/title/AUR_helpers), it's even simpler:**

```bash
paru -S linutil
```

*Replace `paru` with your preferred helper and `linutil` with your preferred package.*
