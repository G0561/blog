---
layout: default
title: 如何搭建自己的blog
comments: true
---


##搭建blog
1. 注册 GitHub，例如你的用户名为 minixbeta
2. 到 StrayBirds 点右上角的 fork
3. 到你 fork 后的项目中，将 _config.yml 中的 username 修改成你的用户名 minixbeta
4. 得到你自己的博客 http://minixbeta.github.io/StrayBirds/
5. 如果你想把项目的名字改了，例如，将 StrayBirds 修改为 blog 那么，你需要做的是:
  
   1. 在项目的 Setting 中将 Repository name 从 StrayBirds 修改为 blog
   2. 将 _config.yml 中的 baseurl 修改为 /blog
   3. 通过 http://minixbeta.github.io/blog/ 来访问你的新博客

##给blog增加评论功能 
    
    1.到这里注册：https://disqus.com/admin/create/ 
    2.添加一个站点，定义一个短名
    3.修改 `_inclusds/comments.ext`，把里面的 `disqus_shortname ` 修改成你的博客短名
    4.启用评论，在写文章的风格定义部分，加上 `comments: true` 

我的blog： http://g0561.github.io/blog/  只要联网就可以访问到的
希望对大家有所帮助，非常感谢原作者开发的这个框架
原文地址：http://blog.csdn.net/on_1y/article/details/19259435#t8
