# Install Guide for HiveOS Proxmox VM
> VM can also be installed in virt-manager (libvirt) too but with a different install process

### Download HiveOS image: 
[hiveos.farm/install](https://hiveos.farm/install/)

### Extract image:
```bash
xz -dv <hiveos image file ending in .xz>

example:
xz -dv hiveos-0.6-212-stable@211201.img.xz
```

### Refer to YouTube video to set up VM:
[https://youtu.be/F7Loqq0v08s](https://youtu.be/F7Loqq0v08s)

### Import image to VM config: 
```bash
qm importdisk <vmid> <source> <storage> [OPTIONS]

example:
qm importdisk 110 ./haos_ova-6.6.qcow2 local-lvm
```
> [Options]=> --format <qcow2 | raw | vmdk>
