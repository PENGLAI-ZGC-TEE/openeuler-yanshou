# rootfs打包
```bash
fakeroot sh -c 'cd rootfs && find . | cpio -o -H newc > ../rootfs.cpio'
```

# dtb生成
```bash
dtc -O dtb -o v3a.dtb nanhu-v3a.dts
```

