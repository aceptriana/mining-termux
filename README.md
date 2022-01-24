# Mining Pake Termux
## Instalasi
```
-  pkg update && pkg upgrade
-  pkg install proot-distro
-  proot-distro install ubuntu
-  proot-distro login ubuntu
```

```
-  apt update 
-  apt upgrade
-  apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
-  apt install nano
-  git clone https://github.com/xmrig/xmrig.git
-  mkdir xmrig/build && cd xmrig/build
-  cmake ..
-  make -j$(nproc)
-  wget https://gist.githubusercontent.com/dytra/5b17acdd38fcabba83e6411f38cce5ad/raw/9214159292a479ec5c27ac7ea28d0da00ca99d4f/config.json
-  nano config.json
-  ./xmrig
```
![alt text](https://github.com/aceptriana/mining-termux/blob/main/acep.png)

unMineable 
[Pilih Koin Yang Mau Di Mining](https://unmineable.com/)
