---
layout: default
title:  "监控平台部署教程"
date:   2019-07-17 1:00:00
categories: main
---

请在这里下载最新版的监控平台部署包（推荐操作方式:在linux系统下可以复制文件链接使用 wget 直接下载）

1、[最新版的后端jar包 cbus-dmp.jar][cbus-dmp.jar];

2、文件名称为 application.yml [最新的配置文件][application.yml];

3、[最新的静态文件代码包 static.zip][static.zip];

[cbus-dmp.jar]: http://218.95.137.107:9000//dhc-dmp/resource/cbus-dmp-1.0.4.jar
[application.yml]: http://140.143.80.97/dhc-dmp/resource/application.yml
[static.zip]: http://218.95.137.107:9000/dhc-dmp/resource/static.zip

请将所有的文件放在同一目录启动，启动前请根据自己的需要修改配置文件

下载完成的项目路径如图所示

<img src="http://140.143.80.97/dhc-dmp/img/1D790ACF-7568-4478-AB3F-C9F79477AC4C.png" height = "200px" />

解压后的目录结构如图所示,如需修改默认的第一层静态文件目录static,请修改 application 中对应的配置项

<img src="http://140.143.80.97/dhc-dmp/img/B83F511A-CC85-4424-B6A0-2B95E6824FE0.png" height = "200px" />

{% highlight ruby %}
spring:
  resources:
    static-locations: file:/Users/zhangzexu/文档/idea/newcbus-dmp/cbus-dmp/target/static
#=> static-locations: file: 后面为静态文件所在的全路径
{% endhighlight %}

上述的文件路径如图所示

<img src="http://140.143.80.97/dhc-dmp/img/24BB5473-896B-4F32-83B7-7778C0D9C384.png" height = "200px" />

修改 file: 后面为 自己statics所在的路径

版本更新日志:

历史版本(说明:后面更新了那个版本就会发布那个版本的更新包)

2019-07-17 (更新说明:第一次公布，后面每次会比较上面一个版本进行内容更新说明)

[cbus-dmp.jar][cbus-dmp.jar]||
[application.yml][application.yml]||
[static.zip][static.zip]

[cbus-dmp.jar]: http://218.95.137.107:9000/dhc-dmp/resource/2019-07-17/cbus-dmp-1.0.4.jar
[application.yml]: http://140.143.80.97/dhc-dmp/resource/2019-07-17/application.yml
[static.zip]: http://218.95.137.107:9000/dhc-dmp/resource/2019-07-17/static.zip




