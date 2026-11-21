# gunmu-WebPlayer
# 震 撼 首 发
**∷-----------------------------------------------∷**
**|      滚木网页播放器        |**
**|     (满屏都是滚木啊!)       |**
**∷-------------------------------------------------|**
**|    如何使用？看下面         |**
**∷-------------------------------------------------∷**

PC和手机在本地用(Port是你的端口，IP是你的IP地址):
如果只是想在本地用一下，不打算对公网开放，请安装python，然后切换到index.html所在的目录，输入命令:
python -m http.server Port

最后访问localhost:Port
对局域网开放，你需要改:
python -m http.server Port --bind IP

对公网开放，就不建议使用Python，你应该换成Nginx或者是其他的服务器软件。服务器软件中一定要允许开启**目录浏览功能**，不然是**无法扫描**到那些音频文件的

ENG:
**∷-----------------------------------------------∷**
**|      gunmu-Webplayer     |**
**|     (ALL GUNMU!)         |**
**∷-------------------------------------------------|**
**|    How to use?           |**
**∷-------------------------------------------------∷**

PC:
You need Install Python, change directory to your folder, and run command:
python -m http.server YourPort --bind YourIP
View Web(IP:Port), select audio file, Then it will start playing
**ONLY LAN!!!!!!!**

支持流媒体:
https://github.com/bilibili-hvuv23544/banli-streamplayer

STREAMsupport:
https://github.com/bilibili-hvuv23544/banli-streamplayer
