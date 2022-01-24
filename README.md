# Mining Pake Termux
Powerd By XMRIG
## Instalasi Ubuntu
```
-  pkg update && pkg upgrade
-  pkg install proot-distro
-  proot-distro install ubuntu
-  proot-distro login ubuntu
```
## Login Ubuntu
```
-  apt update 
-  apt upgrade
-  apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
-  apt install nano
-  git clone https://github.com/xmrig/xmrig.git
-  mkdir xmrig/build && cd xmrig/build
-  cmake ..
-  make -j$(nproc)
-  wget https://raw.githubusercontent.com/aceptriana/mining-termux/main/config.json
-  nano config.json
-  ./xmrig
```
unMineable Mine your favorite non-mineable crypto assets!
[Pilih Koin Atau Token](https://unmineable.com/coins)

## Ubah Config.json nya
![alt text](https://github.com/aceptriana/mining-termux/blob/main/acep.png)

## Demo 
[![Watch the video](https://img.youtube.com/vi/Yn69065wh14/maxresdefault.jpg)](https://www.youtube.com/watch?v=Yn69065wh14)


