--- 
categories: WordPressBackup
date: 2008-10-03 16:05:00 -04:00
layout: post
title: WordPress入门教程
---
这两天有不少对WordPress的感兴趣的朋友来此建站,其中有对WordPress颇有了解的也有和wp"第一次亲密接触"的.为了避免不必要的错误和时间上的浪费,我还是在这里写个入门的教程,简单介绍一下怎样开始使用WordPress.牛人可以直接飘过...

本文内容包括
<a href="#login">登录管理界面</a>
<a href="#theme">更改主题</a>
<a href="#themeeditor">定制主题</a>
<a href="#plugin">插件相关</a>
<a href="#user">修改密码和邮箱</a>
<a href="#manage">搬家和备份</a>
<a href="#write">开始写文章及管理</a>

<!--more-->
<h2 id="login">1.登录管理界面</h2>
地址是 http://你的域名/wp-admin
<h2 id="theme">2.更改blog主题</h2>
所谓主题就是你的blog看起来是什么样子

用你的用户名和密码登录ftp://ftp.azpala.com

解压缩下载的主题文件(你可以去<a href="http://wordpress.org/extend/themes/" target="_blank">这里</a>寻找喜欢的主题),然后将整个文件夹上传到 wp-content/themes/

那里已经有两个备用主题:default和classic,无需删除.

接着转到管理界面http://你的域名/wp-admin,点击<strong>Design</strong>,你就看到所有能用的主题及缩略图.

点击你想使用的主题会出现一个预览界面,觉得合适就点击右上角的激活,否则点击左上角的x关闭预览.
<h2 id="themeeditor">3.定制主题</h2>
在Design页面下还有两个分页面,分别是:Widgets和ThemeEditor.

<img class="alignnone size-full wp-image-836" title="design" src="http://ztnote.files.wordpress.com/2008/10/design.png" alt="" width="320" height="75" />

所谓Widgets就是你放在blog页面侧边栏的东东,比如最新留言啦,最近文章啦.点开后可以看到左侧是所有可用的Widget,右边是你已经使用的.刚开始是空的.点击左侧widget上的add即可以添加到右侧.最后点击右侧列表下的保存.

右侧Widget的排列顺序和你在blog页面上看到的顺序是一致的,想调整顺序的话只需要拖动相关widget就行了.最后也要保存.如果想弃用某些widget,只需点击Edit,然后remove就可以了.

至于ThemeEditor,建议等比较熟悉WordPress后再去修改.这里先不介绍了.
<h2 id="plugin">4.插件</h2>
插件的作用是增加你blog的功能性.

比如在某篇文章下面显示相关文章, 在侧边栏增加投票,或者添加一些其他功能的Widget.

当然,如果你是刚刚使用WordPress,就算不安装任何插件,也没有任何问题.所以建议先略去本项,等你觉得需要添加什么功能时再去搜索相关插件.

你可以先去<a href="http://wordpress.org/extend/plugins/" target="_blank">这里</a>下载你想要的插件.

下载完毕后解压缩,然后将相关文件或文件夹上传到wp-content/plugin里去.具体的安装和使用方法,在你下载的插件页面上都有详细说明.

启用插件需要点击管理页面右上角的plugins,然后你会看到一个插件列表,已经启用的在最上面,没启用的在最下面.
<h2 id="user">5.基本信息的修改</h2>
如果你需要修改密码,邮箱(可以用来找回密码)等资料,需要点击Plugins右侧的Users,点击你的用户名进行修改.
<h2 id="manage">6.导入和导出</h2>
在Manage的页面下有Import和Export,用来导入文章和导出本blog的文章.

WordPress可以很方便的导入其他WordPress导出的文章,或者blogger等网站的文章备份. 如果你想从其他的blog网站搬家的话,需要用一个叫做博客备份软件的东东,详情请见<a href="http://ygc.azpala.com/?p=412" target="_blank">这里</a>.
<h2 id="write">7.写blog及日常管理</h2>
等把一切设置妥当(如果你爱上WordPress系统,似乎没有完全妥当的那一天.因为你总能通过上面几点打造一个最适合自己的独一无二的blog),接下来就是写文章,评论及管理了.

点击Write,就会进入blog文章的编写页面,界面一目了然,不需多介绍.Write下面除了post还有page,你可以用来写写个人介绍啥的.

点击Manage,就可以管理已有的文章,页面及链接等.

点击Comments,可以看到本站的所有评论,然后可以修改,删除,设为垃圾评论等.

右上角的Setting是你的blog的基本设置,可以自己研究一下.