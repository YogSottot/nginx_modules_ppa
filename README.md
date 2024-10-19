A PPA repository for packages:

[libnginx-mod-http-zip](https://github.com/evanmiller/mod_zip)
[libnginx-mod-http-ntlm](https://github.com/gabihodoroaga/nginx-ntlm-module)

Usage

```
sudo curl -SsL -o /etc/apt/trusted.gpg.d/yogsottot.asc https://yogsottot.github.io/ppa/yogsottot.asc
sudo curl -SsL -o /etc/apt/sources.list.d/yogsottot.list https://yogsottot.github.io/ppa/yogsottot.list
sudo apt update
sudo apt install libnginx-mod-http-zip libnginx-mod-http-ntlm
```

Source

https://wiki.debian.org/DebianRepository/SetupWithReprepro
