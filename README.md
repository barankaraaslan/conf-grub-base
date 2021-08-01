# conf-grub-base

This package updates `/etc/default/grub` and creates a directory `/etc/default/grub.d` so that changing default GRUB values such as `GRUB_DISABLE_OS_PROBER` can be done without changing `/etc/default/grub`. Your packages can install files to `/etc/default/grub.d` for updating GRUB values (Similar to /etc/grub.d).