7.无线广播
===========

7.1双板广播通信发送消息（两块掌控板）
------------------------------------

示例
^^^^^
**掌控板A按下A键时，通过无线广播向掌控板B发送“hello”，掌控板B接收到消息后，在OLED屏显示，并播放音乐DADADADUM**


发送端：

.. image:: /sample/image/7.1A.png
   :scale: 100 %

接收端：

.. image:: /sample/image/7.1B.png
   :scale: 100 %

:download:`点击下载示例</sample/example/7.1.zip>`


7.2双板广播通信控制RGB、图像显示
-------------------------------------

示例
^^^^^
**掌控板A通过金手指发送信息控制掌控板B开关三个RGB灯**


发送端：持续群发UDP消息

.. image:: /sample/image/7.2A.png
   :scale: 100 %

接收端：接收UDP消息并显示在掌控板OLED屏中

.. image:: /sample/image/7.2B.png
   :scale: 100 %

:download:`点击下载示例</sample/example/7.2.zip>`