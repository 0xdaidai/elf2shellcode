# elf2shellcode
## 方法1
```sh
make
```

## 方法2
```sh
gcc -no-pie -nostdlib -Ttext 0xc00000 -Wl,--build-id=none -s 
```