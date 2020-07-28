mPython 使用说明测试
====================

软件安装
-----------

目前最新版本为0.1.3，支持Windows 7/8/10、Macos、Linux：

点击链接下载：Win 7/8/10，Mac OS，Linux
* https://cdn.makeymonkey.com/autoUpdate/mpython/mPython%20Setup%200.2.2.exe 
* https://cdn.makeymonkey.com/autoUpdate/mpython/mac/mPython_0.2.2.pkg 
* http://steamaker.oss-cn-shenzhen.aliyuncs.com/autoUpdate/mpython/linux-x64/mPython_linux_0.2.2.tar.xz 

.. Hint::

  安装过程有可能被杀毒软件误报病毒，需要选择“允许程序所有操作”。


安装软件的最后一步，会自动安装CP210x的驱动，如果先前安装过则可以忽略。

.. image:: /images/mPython/software_2.png
    :width: 500px

接入硬件
-----------

点击桌面快捷方式mPython ，打开软件主界面。

.. image:: /images/mPython/mPython_1.png


用USB线接入掌控板。正确识别后，端口自行显示“已连接”，如下图：

.. image:: /images/mPython/mPython_2.png



上述顺序可以颠倒，即：可以先接入掌控，再打开软件。


仿真
-----------

编写代码之后点击右边掌控板的播放按钮。

.. image:: /images/mPython/mPython_fz.png

探究
-----------

如图所示，使用数学分类下面的图表指令，即可实现数据可视化

.. image:: /images/mPython/mPython_tj.png



图形编辑区
-----------

保存
````````

点击“文件”，“保存本地”保存程序对应的代码，后缀为py：

.. image:: /images/mPython/mPython_3.png

点击“文件”，“打开本地”打开保存的py文件：

.. image:: /images/mPython/mPython_5.png

读取效果如图：

.. image:: /images/mPython/mPython_4.png

点击“文件”，“保存本地”保存程序对应的代码及图形化模块，后缀为xml：

.. image:: /images/mPython/mPython_6.png

点击“文件”，“打开本地”打开保存的xml文件，读取效果如图：

.. image:: /images/mPython/mPython_7.png

模块提示
````````
鼠标停留在模块上会有提示：

.. image:: /images/mPython/mPython_8.png

帮助文档
````````
在模块上，点击鼠标右键：

.. image:: /images/mPython/mPython_9.png

点击帮助，即可跳转至帮助文档：

.. image:: /images/mPython/mPython_10.png

切换图形/代码模式
````````

点击“</>代码”，即可实现对应切换：

.. image:: /images/mPython/mPython_11.png

.. image:: /images/mPython/mPython_12.png

改变图形区/代码区大小
````````			

鼠标停留在圈红的灰色三角上，按住左键左右拖动即可：

.. image:: /images/mPython/mPython_13.png


代码编辑区
-----------

代码联想：

.. image:: /images/mPython/mPython_14.png


运行/刷入
-----------

运行/刷入
````````

运行/刷入两种模式皆可实现程序效果。

按钮字样变成“已连接”字样时，即可开始运行/刷入：

.. image:: /images/mPython/mPython_15.png

.. Note::

  “运行”的代码脱机后即失效，“刷入”的代码脱机后再次连接电源仍有效

代码查错
````````

圈红处是反馈的信息，包括硬件信息、代码报错信息等：

.. image:: /images/mPython/mPython_16.png

比如，红字为代码报错信息：

.. image:: /images/mPython/mPython_17.png


烧录固件
-----------

点击“设置”“烧录固件”，选择掌控版官方固件：

.. image:: /images/mPython/mPython_18.png

.. Hint::

  如果烧录固件失败（或超过30秒仍然一直在恢复），请先尝试关闭杀毒软件，或者选择信任esptool。
