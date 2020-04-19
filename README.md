[![Build Status](https://travis-ci.org/abbbi/kiss-bootstrap.svg?branch=master)](https://travis-ci.org/abbbi/kiss-bootstrap)

# kiss-bootstrap
Bootstrap kiss linux into qemu boot and vagrant image

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
