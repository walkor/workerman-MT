workerman-for-win
=================

workerman windows 版本


此版本为window多线程测试版本，请不要用于生产环境

安装
==============
## 1、要求安装php线程安全版
线程安全版本下载页面：[http://windows.php.net/download](http://windows.php.net/download)   
pthreads下载下载页面： [http://windows.php.net/downloads/pecl/releases/pthreads](http://windows.php.net/downloads/pecl/releases/pthreads/)    
![安装线程安全php并设置环境变量](http://www.workerman.net/img/gif/install-php.gif)

## 2、安装pthreads扩展
![安装pthreads扩展](http://www.workerman.net/img/gif/install-pthreads.gif)

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