# Evo-Platform-CLI[Beta]
Version 3 of Evo-Platform. Codename : Lamda Driver

# Requirement

```
apt install build-essential
```

Full mode + QT[for gui]

```
apt install build-essential libqt4-dev qt5-qmake cmake qttools5-dev libqt5webkit5-dev qttools5-dev-tools qt5-default python-sphinx texlive-latex-base inotify-tools openssl libssl-dev libdb++-dev libminiupnpc-dev git sqlite3 libsqlite3-dev g++ libpng-dev gedit python gcc make libbz2-dev libdb-dev libssl-dev  libreadline-dev autoconf libtool libleveldb-dev libblkid-dev e2fslibs-dev libboost-all-dev libaudit-dev automake nano qtbase5-dev qt4-dev-tools libncurses5-dev fakeroot wget bzip2 bison flex dctrl-tools libelf-dev libuv1-dev libmicrohttpd-dev pkg-config libevent-dev libunbound-dev libminiupnpc-dev libunwind8-dev libldns-dev libexpat1-dev doxygen graphviz screen libdb{,++}-dev libzmq3-dev
```

# Installation guide

1. fork this and do clone from yours
2. adding library magic

```
git submodule init
git submodule update --remote
```

Cmake upgrade

```
cd modules/cmake && ./bootstrap && make && make install
```

3. try change setting on src/CryptonoteConfig.h and src/Cmakelist.txt
4. save all
5. run by do ```make```
6. do to build/release/src/ and try ```./daemon --print-genesis-tx```
7. copy that by replace genesis here src/CryptonoteConfig.h
8. recompile again by ```make```
9. run ```./daemon --testnet``` for test. or used ```./daemon```.
10. the magic is you no need 2 seed like bytecoin. used 1 seed is ok!
11. happy used
12. contributor helper : src/contrib.hpp

# Super Nodes Feature

https://github.com/FndNur1Labs/CryptonoteEvo/wiki/Super-Nodes

# Donation For Support

https://goo.gl/forms/3NGyhQr3uXiOMa5u1

Main Page : https://github.com/FndNur1Labs/CryptonoteEvo
