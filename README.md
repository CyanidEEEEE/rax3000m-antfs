# Rax3000m-Antfs
闭源驱动版本，带硬件加速，IP地址和密码均为官方默认自己看，尽量精简，带“passwall”（xray）、samba4、ftp、zerotier、硬件qos、硬盘休眠，很多闭源驱动都用默认配置的ntfs3，但是旧版本内核的ntfs3有点不完善，很容易脏盘，因此改用antfs，速度稍慢，但是用antfs在5.4内核对挂载ntfs硬盘最友好，分有docker和无docker两个版本，也提供ntfs3版本作为实验，在immortalwrt源码更新时会自动更新
