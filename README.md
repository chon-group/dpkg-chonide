# dpkg-chonide
Package for Debian, Ubuntu, Mint, and derivatives of the [ChonIDE - An IDE to Support the Development of Embedded Multi-Agent Systems](https://github.com/chon-group/chonIDE) 

## How to install?

In a terminal, execute the steps described below:

```sh
 echo "deb [trusted=yes] http://packages.chon.group/ chonos main" | sudo tee /etc/apt/sources.list.d/chonos.list 
 sudo apt update 
 sudo apt install openjdk-17-jre chonide 
 sudo reboot 
```

 ## Others links

* [ChonIDE repository](https://github.com/chon-group/chonIDE)

* [Instalation tutorial](https://github.com/chon-group/chonIDE/blob/main/doc/01-installation/debian-and-Ubuntu.md)

* [Hello world](https://github.com/chon-group/chonIDE/blob/main/doc/02-helloWorld/Ubuntu.md)