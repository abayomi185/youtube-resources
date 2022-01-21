### Install: 
https://hiveos.farm/install/

### Extract:
```
xz -dv hiveos-0.6-212-stable@211201.img.xz
```

### Import: 
```
qm importdisk <vmid> <source> <storage> [OPTIONS]
sudo qm importdisk 110 ./haos_ova-6.6.qcow2 local-lvm
```
[Options]=> --format <qcow2 | raw | vmdk>
