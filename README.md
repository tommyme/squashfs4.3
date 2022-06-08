# patched squashfs

```shell
apt-get install build-essential liblzma-dev liblzo2-dev zlib1g-dev
```

```shell
cd squashfs-tools
make && sudo make install
```

删掉了Makefile line 129 `-Werror` 我arm make会有警告
