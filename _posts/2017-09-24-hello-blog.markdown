---
layout:     post
title:      "你好 大二"
subtitle:   " \"Hello World, Hello Blog\""
date:       2017-09-27 21:00:00
author:     "ACsms"
header-img: "img/post-bg-2017.jpg"
catalog: true
tags:
    - 生活
---

> “Yeah It's on. ”


## 前言

土豆 的 Blog 就这么开通了。

[跳过废话，直接看怎么搭建的 ](#build) 


2017年夏末，土豆终于有个地方好好写东西了。。

身为一名弱校自救者，博客这种东西还是要有的，这似乎是很久前就打算做的事了

拖了这么久真是对自己感到抱歉

年初在杭电hdu上刷题的时候，曾在qq空间里写过两篇记录

排版，高亮暂且不说

光是在充满段子鸡汤与魔法的地方发出题来  就已经让我事后尬的头皮发麻

。。。

嘛，被嘲讽的次数已经记不清了

嗯，，不管怎么样

blog算是搭好了，域名还在过审，过两天会绑上

以后也没有借口瞎学不总结了

hello blog

<p id = "build"></p>
---

## 正文

接下来说说搭建这个博客的过程。
GitHub是一个代码托管网站，现在很多开源项目都放在GitHub上。 利用GitHub，可以让全球各地的程序员们一起协作开发。GitHub 提供了一种功能，叫 GitHub Pages, 利用这个功能，我 们可以为项目建立网站，当然，这也意味着我们可以通过 GitHub Pages 建立自己的网站。

github提供免费的开放的空间，不限制流量，大小没有限制.推荐1G以内.达到1G以后会受到GITHUB的通知邮件.上传超过50M的单个文件会warning.无法上传超过100M的单个文件.目前大文件会提供一个1G的免费GIT-LFS空间.

这个空间用来做个人博客再合适不过

1.注册github账号

2.创建新的库，名字  你的用户名.github.io（如果不用自己用户名会打不开网站）

3.进入设置界面，往下拉，找到GitHub pages设置界面，然后点击Choose a theme选择一个博客主题
  到这一步呢，正常来说你就可以看到自己的博客了。在地址栏输入：用户名.http://github.io你就可以访问页面了。

4.然后，去下载GitHub桌面版，为什么使用桌面版呢，因为简单，适合小白，没那么多命令行。
  我的电脑虽然安过 git bash，但是命令行操作对现在的我来说还是困难
         下载下来后，打开用自己的用户名登录。然后选择File下的Clone repositories. 

5.clone完之后你会发现你刚才选择的路径下多了一个文件夹
  这个就是仓库了，有一个隐藏的.get文件夹有，一定不要删掉他，不然仓库就会被破坏掉了
  其余东西就可以删掉了

6.接下来可以去找一个博客模板，如果自己喜欢折腾，也可以自己写  。

7.将博客模板拷贝至仓库文件夹下

8.接下来改同步到网络上了，打开GitHub桌面版。你会发现有非常多的changes，如图
  在summary中随意填一些内容，然后点击commit to master    
  最后点击顶部fetch origin就OK了

9.这时已经可以通过  你的用户名.github.io 来访问博客了

  然后只需要更改文件代码就可以完成博客了（我使用的是sublime2）
  这里需要html css基础，我在暑假学过，所以改起来还算是蛮顺畅的

----

  以上，over。

<!-- UY BEGIN -->
<div id="uyan_frame"></div>
<script type="text/javascript" src="http://v2.uyan.cc/code/uyan.js?uid=2147089"></script>
<!-- UY END -->



