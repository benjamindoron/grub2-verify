# grub2-verify

Includes scripts to enable PGP signature verification in the Grub bootloader

- grub2-switch-to-verify automates the setup of signature verification. It should be executed directly
- grub_verify-kern-postinst signs newly installed kernels. It should be placed in /usr/lib/kernel/install.d/ and named "99-grub_verify.install"
