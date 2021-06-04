6.WIFI
=======

6.1wifi时钟
---------------

示例
^^^^^
**连接wifi并同步为东8区时区，在掌控板OLED屏第一行显示当前日期，第二行显示当前时间**

.. image:: /sample/image/6.1.png
   :scale: 100 %

:download:`点击下载示例</sample/example/6.1.mxml>`


6.2wifi通信发送消息（两块掌控板）
----------------------------------

示例
^^^^^

**在WIFI下，使用掌控板A向掌控板B持续发送讯息“zhangkongban”，掌控板B在收到消息后将其显示在OLED屏中**

发送端：持续群发UDP消息

.. image:: /sample/image/6.2A.png
   :scale: 100 %

接收端：接收UDP消息并显示在掌控板OLED屏中

.. image:: /sample/image/6.2B.png
   :scale: 100 %


:download:`点击下载示例</sample/example/6.2.zip>`


6.3双板通信控制RGB、图像显示（两块掌控板）
----------------------------------

示例1 双板通信控制RGB 
^^^^^

**掌控板A当A键按下时，发送指令“open”打开掌控板B所有RGB灯，当B键按下时，发送指令“close”关闭掌控板B所有RGB灯**

发送端：

.. image:: /sample/image/6.3.1.png
   :scale: 100 %

接收端：

.. image:: /sample/image/6.3.2.png
   :scale: 100 %

:download:`点击下载示例</sample/example/6.3A.zip>`

示例2 双板通信控制图像显示
^^^^^

**掌控板A当A键按下时，发送指令“show”在掌控板B OLED屏中绘制心形图案，当B键按下时，发送指令“clear”清除掌控板B OLED屏中所有图像**

发送端：

.. image:: /sample/image/6.3.3.png
    :scale: 100 %

接收端：

.. image:: /sample/image/6.3.4.png
    :scale: 100 %

:download:`点击下载示例</sample/example/6.3B.zip>`