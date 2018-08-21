---
layout:     post
title:      "Welcome to Steven Ji's Blog"
subtitle:   " \"create blog in github.io\""
date:       2018-08-21 19:00:00
author:     "steven"
header-img: "img/post-bg.jpg"
tags:
    - Software
---

> “Yeah It's on. ”


## Install


安装就是按照refence说明来做就行，主要步骤：
1. 在自己的github上创建rep，名字是stevenji.github.io ,这里username替换为自己的github用户名
   `$ git clone git@github.com:stevenji.github.io.git`  #clone repo to local
2. clone一个主题
   `$ git clone git@github.com:Huxpro/huxblog-boilerplate.git` #clone theme to local`
3. 把这个主题push到我自己创建的stevenji.github.io这个repo
   `$ cd huxblog-boilerplate.github.io`
   `$ git remote add mine git@github.com:steven/stevenji.github.io.git
以上三步其实就可以看到自己的blog了！
注意：
  如果遇到访问不了情况，可以参考修改CNAME



<p id = "build"></p>
---

## 写blog

接下来就可以修改配置文件。
1. _config.yml
    
2. index.html

3. image目录中的图像

然后就可以写blog了，注意格式是markdown

* **Markdown** 带来的优雅写作体验
* 非常熟悉的 Git workflow ，**Git Commit 即 Blog Post**
* 利用 GitHub Pages 的域名和免费无限空间，不用自己折腾主机
	* 如果需要自定义域名，也只需要简单改改 DNS 加个 CNAME 就好了
* Jekyll 的自定制非常容易，基本就是个模版引擎


注意：
  所有的blog都是放在_post目录下，格式是markdown，并且命名方式是`year-month-day-title.markdwon`的形式


---



## 参考
1. [如何快速搭建自己的github.io博客]https://blog.csdn.net/walkerhau/article/details/77394659?utm_source=debugrun&utm_medium=referral)
2. [利用 GitHub Pages 快速搭建个人博客](https://www.jianshu.com/p/e68fba58f75c)
 
