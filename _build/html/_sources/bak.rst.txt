章节1
=====================================
asas 
as 


开始
------
dddddd


  *sss*

 **dfgdfgdfgdfg**

  ``sdsdsdsdsdsdsd``

安装
------------

  pip install sandglass


概览
--------

**sandglass(沙漏)** 是一个增强的、友好的时间处理库，目的是为了解放程序员的生产力。
在python中有太多处理时间的库，datetime/date/time/calendar等等。需要记的细节太多，选择困难。
而sandglass就是解决这个的青霉素。从各种麻烦的转换中解脱出来。
只需记住 **Sandglass对象** 和 **ben()** 、 **tslice()** 、 **cronwalk()** 这几个主要的api即可。

特性
----------
 + api简洁，开箱即用
 + 增强接管datetime
 + (此次略去xx字)

快速上手
---------
在sandglass中，核心对象是 **Sandglass对象** 。通过这个对象，可以方便的获取各个时间属性和操作::
    
    #获取属性
    >>>sg = ben('2013,1,1 13:14:15')
    >>>sg.year,sg.month,sg.day,sg.hour,sg.minute,sg.second,sg.microsecond
    (2013, 1, 1, 13, 14, 15, 0)
    (此次略去xx字)

API文档
-----------------

.. toctree::
   :maxdepth: 2

   api

Todo
---------
* Add timezone support

Changelog
---------
**0.0.1**

* Initial release

