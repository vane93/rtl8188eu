
rtl8188eu（文某人的站点：www.muziwen.com 欢迎交流）
=========

Repository for the stand-alone RTL8188EU driver.

Compiling & Building
---------
### 1 Dependencies
To compile the driver, you need set up local yum，and install it by

> $sudo yum install gcc make 

In addition,

you must have the kernel headers installed. you can set up local yum ,and install it by 

> $sudo yum install kernel-headers kernel-devel

If you have done these steps， you can skip it

### 2 Download

> git clone https://github.com/vane93/rtl8188eu.git
### 3 Compiling

> cd rtl8818eu/

> make all

### 4 Installing

> sudo make install

### 5 import

> insmod 8188eu.ko

### 6 test
> ifconfig 

  you will find wlan0.

### enjot it!
