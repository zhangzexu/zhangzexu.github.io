---
layout: default
title:  "cbus-dmp download"
date:   2016-02-12 17:50:00
categories: main
---

请在这里下载最新版的监控平台部署包

1、[最新版的后端jar包 cbus-dmp.jar][cbus-dmp.jar];

2、文件名称为 application.yml [最新的配置文件][application.yml];

3、[最新的静态文件代码包 static.zip][static.zip];

请将所有的文件放在同一目录启动，启动前请根据自己的需要修改配置文件

下载完成的项目路径如图所示

<img src="http://140.143.80.97/dhc-dmp/img/1D790ACF-7568-4478-AB3F-C9F79477AC4C.png" width = "100" height = "100" />


{% highlight ruby %}
spring:
   resources:
     static-locations: classpath:./static
{% endhighlight %}



[cbus-dmp.jar]: http://140.143.80.97/dhc-dmp/resource/cbus-dmp-1.0.4.jar
[application.yml]: http://140.143.80.97/dhc-dmp/resource/application.yml
[static.zip]: http://140.143.80.97/dhc-dmp/resource/static.zip
