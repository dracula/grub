### [GRUB](https://gnu.org/software/grub/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone https://github.com/dracula/grub.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/grub/archive/master.zip) option and unzip them.

#### Activating theme

1. Move the dracula folder to /usr/share/grub/themes/
2. Change the theme in /etc/default/grub ( Set GRUB_THEME to '/usr/share/grub/themes/dracula/theme.txt')
3. Run `sudo grub-mkconfig -o /boot/grub/grub.cfg`
