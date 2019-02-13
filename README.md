#### 1.安装deb包
sudo dpkg -i XXXX.deb


#### 2.安装boost
https://blog.csdn.net/xuehuafeiwu123/article/details/78611203  
https://www.boost.org/users/history/version_1_69_0.html  
下载1.69版本  
解压 tar -xf Boost_1_65_1.tar.bz2  
进入boost文件夹  
sudo ./bootstrap.sh  
sudo ./bootstrap.sh --prefix=/usr/local/lib/boost  
接着./b2 install  
头文件在  
/usr/local/lib/boost/include  
二进制文件在  
/usr/local/lib/boost/lib  
查看安装目录中有没有头文件，有则成功  
在include文件夹中  
ls b*  
Boost库是一个可移植、提供源代码的C++库，作为标准库的后备，是C++标准化进程的开发引擎之一  

#### 4.更改文件权限
chmod 777  文件或目录  

#### 5.强行关掉某个进程  
kill -9 12767  
12767是某个进程程序的ID  

#### 6.各种解压  
tar -xf all.tar  
gzip -d all.gz  
gunzip all.gz  
tar -xzf all.tar.gz  

#### 7.wget用法：  
wget http://www.linuxsense.org/xxxx/xxx.tar.gz url地址
-b：后台下载，Wget默认的是把文件下载到当前目录。
-O：将文件下载到指定的目录中。
-P：保存文件之前先创建指定名称的目录
-r 递归下载





