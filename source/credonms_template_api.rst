template结构
=========================
* base.html
  
    负责提供基础的页面结构。

    * rootid: 指定页面使用哪种模板样式，继承需要声明，类型为css的id。
    * header_title: 页面的名称。
    * header_description: 页面的描述。

* credonms_base.html

    提供credonms所需的topnav部分。

    * page: 当前的page, page列表在config.py中。

* credonms.html

    提供topfilter部分和页面样式。

    * topfilter_title 重写以获得filter的名称。


* credonms_add.html

    增加cnu\clt设备界面。
