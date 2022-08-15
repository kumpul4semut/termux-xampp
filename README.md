Repositori for install apache, mysql, php and phpmyadmin on termux.

## Instalasi
Instalation in termux, run command below:

```
pkg install git -y && cd ~/ && git clone https://github.com/kumpul4semut/termux-xampp.git && cd ~/termux-xampp && bash setup && cd ~/ && rm -rf termux-xampp
```

## usage
Change password mysql
```
bash setup_password your_password
```
Directory for your code php on.
```
cd /sdcard/htdocs
```