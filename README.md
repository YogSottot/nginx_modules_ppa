A PPA repository for packages:

[libnginx-mod-http-zip](https://github.com/evanmiller/mod_zip)  
[libnginx-mod-http-ntlm](https://github.com/gabihodoroaga/nginx-ntlm-module)  
[libnginx-mod-http-zstd](https://github.com/tokers/zstd-nginx-module)

Usage

```
sudo curl -SsL -o /etc/apt/keyrings/yogsottot.asc https://yogsottot.github.io/ppa/yogsottot.asc
# for debian 12
sudo curl -SsL -o /etc/apt/sources.list.d/yogsottot.list https://yogsottot.github.io/ppa/yogsottot_debian12.list
# for ubuntu 24.40
sudo curl -SsL -o /etc/apt/sources.list.d/yogsottot.list https://yogsottot.github.io/ppa/yogsottot_ubuntu24.04.list
sudo apt update
sudo apt install libnginx-mod-http-zip libnginx-mod-http-ntlm libnginx-mod-http-zstd
```

Source

https://wiki.debian.org/DebianRepository/SetupWithReprepro
