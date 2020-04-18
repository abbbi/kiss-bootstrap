# kiss-bootstrap
Bootstrap kiss linux into qemu boot image, needs some more work here and there but works :)

```
kiss-bootstrap --build=[all|download|prepare|chroot|qemu]
  all: complete build of chroot/qemu image
  download: download needed components
  prepare: extract archives, create folders
  chroot: build kiss environment in chroot
  qemu: turn chroot into bootable qemu image

./kiss-bootstrap --cleanup
  cleanup
```
