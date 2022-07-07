# isaos
isaos is a mini OS.



# note

## day1

lld-linkが入っていなかったため apt-getでinstallする
```
$ sudo apt-get update -y
$ sudo apt-get install -y lld
```

## day2
- $HOME->$OS_DIRに置き換えて読む
- qemunでテストしたい場合のコマンド
```
$ ~/osbook/devenv/run_qemu.sh ~/edk2/Build/MikanLoaderX64/DEBUG_CLANG38/X64/Loader.efi
```




# Reference
- ゼロからの自作OS入門
- https://github.com/sarisia/mikanos-docker
