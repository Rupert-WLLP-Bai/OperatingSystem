```shell
sudo apt install bochs
sudo apt install bochs-x
```

```shell
nasm boot.asm -o boot.bin
```

```shell
dd if=boot.bin of=a.img bs=512 count=1 conv=notrunc
```

```shell
bochs -f bochsrc
```