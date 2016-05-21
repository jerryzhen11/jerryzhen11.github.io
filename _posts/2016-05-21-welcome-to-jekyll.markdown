---
layout: post
title:  “how to build blog!"
color:  teal
width:   6 
height:  1
date:   2016-05-21 11:31:49 +0200
categories: technique
---
以后每次技术文都会双语写下
说说我第一次搭建blog的过程吧。主要是通过python静态blog框架搭建，外观主要通过sass和responsive处理。推荐大家sass用compass responsive的话我这边用了媒体查询，其实我觉得用bootstrap的网格模型也不错。我这边模仿着写了个类似的col类。其实也就是差不多的意思。
This is mainly about how to build my blog. Actually it's launched by a static python blog framework. For the reason why i use this framework is that it don't need a database to save blogs.I just remember last week period i used node.js and express and mongodb to build a chartroom. The mongo extensions really bothered me and affect the performance of the site. Through sass and responsive design I decorated this and regards to sass ,I recommend using compass combined with sass. I didn't choose bootstrap because I imitate writing a col class.

下面说一下compass的安装。依赖于gem（ruby）
{% highlight ruby %}
sudo gem install compass
国外的gem源可能比较慢
不翻墙的话可以用国内淘宝内部的gem源替换官方的ruby源
据说淘宝写了脚本每隔1小时便会同步一次。
compass -watch （可以实时监听sass的变动并生成相应的css）
{% endhighlight %}
