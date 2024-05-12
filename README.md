# optiarch
A tool for fast optimization of Arch

```
   ____        __  _    ___              __   
  / __ \____  / /_(_)  /   |  __________/ /_  
 / / / / __ \/ __/ /  / /| | / ___/ ___/ __ \ 
/ /_/ / /_/ / /_/ /  / ___ |/ /  / /__/ / / / 
\____/ .___/\__/_/  /_/  |_/_/   \___/_/ /_/  
    /_/                                       
   >>>   A tool for fast optimization of Arch
Made with love by Alexeev Bronislav
```

 > [!WARNING]
 > OptiArch support only Arch Linux

> [!CAUTION]
> This is not stable, optiarch in dev phase.

Big thanks for Arch Linux devs!

## Install
Step 0: install reqs and deps:

```bash
./optiarch.bash --base
```

Launch `optiarch.bash`:

```bash
./optiarch.bash --help
```

> [!TIP]
> After all, start clean.sh script for system cleaning

## Scripts

 + `optiarch.bash` - main script
 + `clean.sh` - script for system cleaning
 + `check-cpu.sh` - check CPU vendor
 + `check-gpu.sh` - check GPU vendor

## Functional

 + [CachyOS Kernel](https://github.com/CachyOS/linux-cachyos) installing
 + Automatic ucode installing (amd&intel)
 + Automatic videodriver installing (amd&intel)

## ToDo

 + Support more CachyOS Kernels
 + Support param GRUB_CMDLINE_LINUX_DEFAULT

# Credits

 + [Cachy OS](https://github.com/CachyOS)
 + [ArchWiki - improving performance](https://wiki.archlinux.org/title/improving_performance)
 + [Arch Linux Optimization Guide (RU)](https://ventureo.codeberg.page/v2022.07.01/source/first-steps.html)
