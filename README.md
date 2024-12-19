

1.地址
  
      https://ghproxy.net/https://raw.githubusercontent.com/xiatian0502/vv/refs/heads/main/itvlist.m3u

  
2.方法：

  windows电脑：
  
      1.1 电脑安装最新的chrome，同时执行文件目录下要有对应版本的chromedriver.exe，
      1.2 下载windows目录下的itv.exe及itvtest.exe,
      1.3 首先运行itv.exe，完成后再运行itvtest.exe，
      1.4 运行完成后在当前目录下生成电视直播文件itvlist.txt。
  
 python的电脑：
  
      2.1 电脑安装chrome，下载对应版本的chromedriver
      2.2 下载itv.py cctv.py weishi.py qita.py
      2.3 pip install selenium requests futures eventlet opencv-python
      2.4 依次运行itv.py cctv.py weishi.py qita.py
      2.5 运行完成后在当前目录下生成电视直播文件itvlist.txt。

3.docker：

        1.安装：docker pull liuxipo/itvall:latest
        2.运行：docker run -v /www/itvall:/app itvall
        3.访问：http://本地ip/itvall/itvlist.txt
  
4.推荐在本地电脑运行，不推荐在github运行。github获得的数据不准确，测速不准。

5.udpxy目录为部分组播源。

