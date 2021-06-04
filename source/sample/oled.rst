
1.OLED显示
===========

1.1文字显示
------------

示例1
^^^^^

**在掌控板OLED屏上第二行显示“掌控板”**

.. image:: /sample/image/1.1.png
   :scale: 100 %

1. 清空OLED显示屏
   

2. 设置掌控板OLED屏第二行文字


3. OLED显示生效

:download:`点击下载示例</sample/example/1.1.mxml>`

1.2图形显示
-----------

示例2
^^^^^

**在掌控板OLED屏中心显示心形图案**

.. image:: /sample/image/1.2.png
   :scale: 100 %

1. 清空OLED显示屏
   

2. 设置掌控板OLED屏图案


3. OLED显示生效

:download:`点击下载示例</sample/example/1.2.mxml>`

1.3交互式图像显示（AB键，金手指，三轴加速度计）
-----------------------------------------------

示例1
^^^^^
**使用A、B键完成显示心跳动画**

.. image:: /sample/image/1.3A.png
   :scale: 100 %

1. 设置A、B键被按下时对应执行的程序
   

2. 设置掌控板OLED屏显示图案，OLED显示生效

3. 交替按下A、B实现OLDE屏图案交替，模拟心跳的样子

:download:`点击下载示示例</sample/example/1.3A.mxml>`


示例2
^^^^^
**使用金手指在屏幕第三行逐步显示“爱上掌控版！”，字间间隔一个字**


.. image:: /sample/image/1.3B.png
   :scale: 100 %

1. 设置P、Y、T、H、O、N键被按下时对应执行OLED屏需要显示的文字和位置
   

2. 显示生效

:download:`点击下载示例</sample/example/1.3B.mxml>`


示例3
^^^^^
**使用加速度计使得当掌控板倾斜时，在OLED中用箭头显示倾斜方向**


.. image:: /sample/image/1.3C.png
   :scale: 100 %

1. 设置P、Y、T、H、O、N键被按下时对应执行OLED屏显示的文字和位置
   

2. 显示生效

:download:`点击下载示例</sample/example/1.3C.mxml>`


1.4动画、滚动字幕
-------------------
示例
^^^^^
**将“掌控板，掌控未来！”从OLED屏底端开始向上滚动**


.. image:: /sample/image/1.4.png
   :scale: 100 %

1. 掌控板OLED分辨率128*64，使用一个变量a代表文字显示在y轴的位置
   

2. 使用循环使OLED文字从OLED底部运动到顶部，每次循环变量a减一

:download:`点击下载示例</sample/example/1.4.mxml>`