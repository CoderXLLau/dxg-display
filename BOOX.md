# 改造电纸书为显示器的软件 #
支持文石96、MAX等安卓系统电纸书，KINDLE DXG或者DX请点击[非VNC改造DXG为显示器](https://github.com/nahtethan/dxg-display/blob/master/DXG.md)。
## 安装步骤，咨询请加电子墨水显示软件QQ群：326606690 ##
1. 电纸书上打开USB调试：设置 - 扩展 - 应用设置 - USB调试
2. 电纸书USB连接PC，弹出的USB存储的框选取消：  
![](https://github.com/nahtethan/dxg-display/blob/master/99-pictures/storage.jpg)
3. Windows安装[豌豆荚](http://mir.wandoujia.com/getwdj/homepage_)，确认豌豆荚可以通过USB连接电纸书。
4. 电纸书上安装安卓软件[TwoDG2.apk](https://raw.githubusercontent.com/nahtethan/dxg-display/master/00-binary/TwoDG2.apk)。
5. PC下载压缩文件[mirror.zip](https://raw.githubusercontent.com/nahtethan/dxg-display/master/00-binary/mirror.zip)。如下图所示，解压缩到c盘。  
![](https://github.com/nahtethan/dxg-display/blob/master/99-pictures/mirror.jpg)
6. [Windows打开命令行](http://jingyan.baidu.com/article/a501d80ce26fecec630f5ee0.html)。如下图所示，在命令行里执行adb devices，确定adb能连接电纸书。  
![](https://github.com/nahtethan/dxg-display/blob/master/99-pictures/adb.jpg)
7. 双击第5步下载的mirror.exe，电纸书将镜像显示器上的内容。（注意：上面下载的apk是试用版，电纸书只显示一半，[正式版点我](https://item.taobao.com/item.htm?id=520024244524)）  
![](https://github.com/nahtethan/dxg-display/blob/master/99-pictures/mirror.jpg)
8. 效果（Max支持分辨率：1600x1200，1376x1032，1200x900，1024x768，800x600）：  
![](https://github.com/nahtethan/dxg-display/blob/master/99-pictures/max.jpg)
