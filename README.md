# stagebuilder
Stagebuilder takes a Gentoo stage3 seed and turns it into a deployable stage4. It is up to you to customize it to your own purposes. As provided here, it creates the stage4 tarball for decibel Linux (https://decibellinux.org).

Also provided are the installer files used for decibel Linux.

## scripts
 * **autobuild.sh** and **chroot_autobuild.sh** Scripts for building a stage4
 * **install_dblinux.sh** and **chroot_install.sh** decibel Linux installer scripts for modern x86_64 EFI systems (EFI, grub, systemd).
 * **cleanup_only.sh** Use this script if you need to force autobuild to quit before it's done, or if autobuild exits unexpectedly.

## license
LICENSE: GNU GPL v.3 (https://www.gnu.org/licenses/gpl-3.0.html#license-text)

DISCLAIMER: No warranties or guarantees are made. This code is provided as-is. Use at your own risk. decible Linux is built in a virtual machine so as not to adversely impact my own computers if anything goes wrong. 

As a side note, NEVER try to manually rm -rf the stage4 build dir unless dev, sys, proc, and run have been umounted from it. 

## versioning
This software is not versioned.
