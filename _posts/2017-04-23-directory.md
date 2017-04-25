---
layout: post
title: ubuntu系统目录结构
subtitle: 系统目录
author: wetson
date: 2017-04-23 13:32:29 +0800
categories: 
tag: 
---
ubuntu没有盘符的概念，只有一个根目录/，所有文件都在它下面  
	
	/			根目录
	
		bin		基本的系统程序

		sbin		超级用户指令，用于系统管理

		boot		内核和启动程序
			
			grub	引导器相关文件

		dev		设备文件
	
		etc		系统软件的启动和配置文件，系统在启动过程需要读取的文件

		home		用户的主目录

		lib		系统程序的库文件，存放系统最基本的动态链接共享库

		media		挂载媒体设备，如光驱、U盘等

		mnt		让用户临时挂载别的文件系统，如双系统时window的某个分区

		opt		可选的应用软件包

		proc		系统内存的映射，可以直接访问来获取系统信息，内存的数据

		sbin		管理员系统程序

		sys		设备目录树，反映当前所接的设备

		tmp		临时文件夹
	
		usr		大多用户程序和文件都在这个目录下
			bin	应用程序

			game	游戏程序

			include	各种头文件，编译文件时需要使用	
			
			lib	应用程序的库文件
			
			lib64	
			
			local	相对usr通常只包含系统自带程序，此目录则是本地管理员用来自由添加程序的
			
			sbin	用户安装系统管理程序
		
			share	包含个应用程序共享资源文件，如字体，图标等

			src	源代码
			
		var		动态数据，登录文件或错误信息文件，数据库或者用户未读邮件默认的存放在这个目录的子目录下
		
		lost_found	磁盘修复文件，存放因非法关机而丢失的文件

### 可执行文件目录的区别
+  **/bin**是系统的一些指令。bin为binary的简写主要放置一些系统的必备执行档例如:cat、cp、chmod df、dmesg、gzip、kill、ls、mkdir、more、mount、rm、su、tar等。
+  **/sbin**一般是指超级用户指令。主要放置一些系统管理的必备程式例如:cfdisk、dhcpcd、dump、e2fsck、fdisk、halt、ifconfig、ifup、 ifdown、init、insmod、lilo、lsmod、mke2fs、modprobe、quotacheck、reboot、rmmod、 runlevel、shutdown等。
+ **/usr/bin**　是你在后期安装的一些软件的运行脚本。主要放置一些应用软体工具的必备执行档例如c++、g++、gcc、chdrv、diff、dig、du、eject、elm、free、gnome*、 gzip、htpasswd、kfm、ktop、last、less、locale、m4、make、man、mcopy、ncftp、 newaliases、nslookup passwd、quota、smb*、wget等。
+ **/usr/sbin**   放置一些用户安装的系统管理的必备程式例如:dhcpd、httpd、imap、in.*d、inetd、lpd、named、netconfig、nmbd、samba、sendmail、squid、swap、tcpd、tcpdump等。

###	待续更新
							
