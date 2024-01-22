# qemu-custom-builds

This is my list for remembering how to build some tricky images using `qemu`.

## Disks
Create a default disk image

```bash
qemu-img create debian.img 20G
```

#### Create qcow2 disk format

```bash
qemu-img create -f qcow2 debian.img 20G
```