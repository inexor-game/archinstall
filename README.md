# archinstall

a small script to bootstrap archlinux in minutes. This is used to bootstrap the Archlinux inexor-machines.

My work is licensed under the MIT-License.

## The installation procedure

* Download the [Archlinux-ISO](https://www.archlinux.org/download/)
* Boot the ISO
* `wget -O install.sh http://git.io/vE3v4`
* Edit `install.sh`
    * use your favorite editor
    * the values are self-explaining
* `chmod +x install.sh`
* `./install.sh`
* reboot your system

## The installed flavor
* mainly default installation-guide, everything parameterized
* partitions (msdos)
    * boot-partition: size parametrized, FS parametrized
    * root-partition: size parametrized, FS parametrized
* network
    * systemd-networkd (auto-generated file with manual edit)
    * systemd-resolved
* sshd enabled
