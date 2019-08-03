# rtl8192EU-linux
Driver for D-Link DWA-131 on Debian Buster (4.19.0-5-amd64)<br/>
The initial code is taken from https://support.dlink.com/ProductInfo.aspx?m=DWA-131<br/>
It relates to hardware revision E: Driver | Linux (4.3.1.1)  10/16/14<br/>
It is/was present in: ftp://ftp2.dlink.com/PRODUCTS/DWA-131/REVE/DWA-131_REVE_DRIVER_v4.3.1.1_LINUX.zip 
```
   -> DWA-131_REVE_DRIVER_v4.3.1.1_LINUX.zip
       -> 20140812_rtl8192EU_linux_v4.3.1.1_11320.tar.gz
```



To compile:
```
 git clone https://github.com/nicsor/rtl8192EU-linux.git
 cd rtl8192EU-linux
 make all
 sudo make install
 ```

Seems to be working ok. These commits were made possible by this update :)
