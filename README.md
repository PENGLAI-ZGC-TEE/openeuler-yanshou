# rootfs打包
```bash
fakeroot sh -c 'cd rootfs && find . | cpio -o -H newc > ../rootfs.cpio'
```
