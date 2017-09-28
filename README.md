rtl8188eu
=========

Repository for the stand-alone RTL8188EU driver.

Compiling & Building
---------
### Dependencies
To compile the driver, you need set up local yum，and install it by

> $sudo yum install gcc make 

In addition,

you must have the kernel headers installed. you can set up local yum ,and install it by 

> $sudo yum install kernel-headers kernel-devel

If you have done these steps， you can skip it

### Download

> git clone https://github.com/vane93/rtl8188eu.git
### Compiling

> cd rtl8818eu/

> make all

### Installing

> sudo make install

### import

> insmod 8188eu.ko

### test
> ifconfig 

  you will find wlan0.

### enjot it!
