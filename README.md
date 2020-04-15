# kiss-bootstrap
Bootstrap kiss linux into qemu boot image

```
kiss-bootstrap --build=[all|download|prepare|chroot|qemu|cleanup]
  all: complete build of chroot/qemu image
  download: download needed components
  prepare: extract archives, create folders
  chroot: build kiss environment in chroot
  qemu: turn chroot into bootable qemu image
  cleanup: clean everything up
```
