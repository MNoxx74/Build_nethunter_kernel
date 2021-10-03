# NetHunter Kernel Builder  
![Kali NetHunter](https://gitlab.com/kalilinux/nethunter/build-scripts/kali-nethunter-project/raw/master/images/nethunter-git-logo.png)  
## Content

## Installation

Clone this repository into your kernel source tree, e.g.
Rename Kernel Source Folder to Nethunter-kernel

``` bash
cd Nethunter-kernel
git clone https://github.com/MNoxx74/Build_nethunter_kernel.git
```

**cd** into `Build_nethunter_kernel/`, open `config` and make sure that you are happy with all the settings.

Important: Changes should not be made in this file. Copy it accross to `local.config` and delete everything except the parameters you would like to change. Change those parameters and save it.

The settings in `local.config` overwrites `config` but will itself not be overwritten by updates.

