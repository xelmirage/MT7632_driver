# MT7632_driver
本驱动支持mt7632 mt7612 mt7662,默认是mt7632，其他版本请修改Makefile文件的CHIPSET  最前面的一个是支持的驱动。
驱动编译

>make

驱动安装

>make install

make install后需要将  MT76x2_driver-master/mcu/bin/   里面的文件复制到  /lib/firmware/

最后一步

进入驱动os/linux目录找到后缀为ko的文件，记住文件名执行下面的命令

>insmod ***.ko

完成驱动安装
