workerman-for-win
=================

workerman windows 版本


此版本为window多线程测试版本，请不要用于生产环境

安装
==============
## 1、要求安装php多线程安全版本及pthreads扩展，并设置php环境变量
PHP5.6线程安全版本下载链接：[http://windows.php.net/download](http://windows.php.net/download)   
pthreads2.0.9 for php5.6 下载链接： [http://windows.php.net/downloads/pecl/releases/pthreads](http://windows.php.net/downloads/pecl/releases/pthreads/)    
![安装线程安全php及pthreads](http://www.workerman.net/img/gif/install-php-pthread.gif)

## 2、设置php.ini，开启sockets、pthreads扩展
![设置php.ini](http://www.workerman.net/img/gif/php-ini-config.gif)

## 3、下载workerman-for-win并启动
![启动workerman-for-win](http://www.workerman.net/img/gif/run-todpole-for-win.gif)


## 其它相关链接
  * [PHP其它版本链接](http://windows.php.net/download/)
  * [pthreads其它版本链接](http://windows.php.net/downloads/pecl/releases/pthreads/)

启动
=======
  * 打开workerman-for-win的文件夹，双击start.bat 即可启动

停止
======
  * 启动后看到一个终端界面，按ctrl+c停止服务；或者点击右上角关闭图标停止服务

说明
======
workerman windows多线程版本接口上与linux多进程版本是兼容的，一般来说在windows版本上开发的程序也可以在linux多进程版本中运行。  
下载pthreads扩展时，注意扩展与你的php版本一致，并且与你系统的位数一致（32位系统为x86；64位系统为x64）