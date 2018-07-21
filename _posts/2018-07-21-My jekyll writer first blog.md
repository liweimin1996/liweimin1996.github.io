---
title: Jekyll Writer详细使用教程及
layout: post
categories: ''
tags: ''
---
# 这是我用jekyll writer写的第一篇博客。
   

    

## 文章出自Min个人博客，转载请申明。

   

###  我最近一直在用visual studio code来写我的网站，VS code用起来真的不错，而且是微软开源的一个软件。不过我在写博客时，markdown格式的md文件写起了怪怪的，我本人比较喜欢所见即所得的word类型的写作方式，但是一直没有什么好的软件来替代。直到最近一个偶然的机会用到了jekyll writer，感觉十分适合习惯word模式的程序员。
    网上关于jekyll writer的相关教程较少，而且也十分模糊，所以我便写了这篇博客。

    

## 关于Jekyll

    

### Jekyll是一个简单免费的生成博客网页的工具，可以绑定github，详情参考官网：https://jekyllrb.com/, 也有一个中文版的：https://www.jekyll.com.cn/ 方便阅读。我的博客就是通过jekyll建立了，上面那个主题网站也是jekyll的，还有一个类似的工具叫“hexo”，自行了解。
    上传修改后的文件到github仓库后需要一段时间才能看到网页的变化或修改效果，所以可以选择安装本地jekyll工具进行本地快速预览。

##     写博客与上传

   

###  Markdown基础
    Jekyll使用Markdown语言书写博客，markdown是一种简单易读的标记性语言，不同于 html，大量的标签不易于阅读，写着也麻烦，用markdown写博客很合适。
    首先你需要了解一些markdown语法，这里有完整版语法说明：
    https://sspai.com/post/25137
    https://blog.csdn.net/KNIGH_YUN/article/details/79733814，了解一些基础后就可以开始写博客了。


##     工具介绍

   

###  网络上有一些好用的markdown编辑器，自行选择。 
    不过每次都用编辑器写好 .md 文件然后用 git 上传到 github 根目录下的 _post 文件夹好像很繁琐，Jekyll官方提供了一款方便的博客编辑器，方便书写、预览、上传，官网链接：http://jekyllwriter.com/，三种系统版本都有。接下来简单介绍一些使用：

    安装后主界面：
    ![Image Title](https://img-blog.csdn.net/20180401093410604?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0tOSUdIX1lVTg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
    添加账号
    ![Image Title](https://img-blog.csdn.net/20180401093825352?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0tOSUdIX1lVTg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
    配置 token
    ![Image Title](https://img-blog.csdn.net/20180401094705731?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0tOSUdIX1lVTg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
    保存后会生成一个 token ，返回软件粘贴进输入框就行了
    ![Image Title](https://img-blog.csdn.net/20180401094911796?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0tOSUdIX1lVTg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
    写完后保存并上传
    ![Image Title](https://img-blog.csdn.net/20180401094200638?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0tOSUdIX1lVTg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
    可以在这里查看和修改账户下的博客
    ![Image Title](https://img-blog.csdn.net/2018040109525674?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0tOSUdIX1lVTg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
    软件其他功能还在完善，自行摸索

##     图床介绍

    

### 写博客就无法避免上传图片，图床就是这么一个地方，就是一个网站，你发自己的图片上传到它的网站，然后它给你一个这个图片的链接，插入博客中就能显示图片了。

    推荐一个知名的，七牛云https://portal.qiniu.com/，注册完实名认证后有一些优惠。 
还有一个神奇的网站：https://sm.ms/，也能用

    然后在 jekyll writer中配置一下： 
    ![Image Title](https://img-blog.csdn.net/20180401100517435?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0tOSUdIX1lVTg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

##     关于图片尺寸

    

### markdown的图片插入方式 ![title](http://xxx.com/xxx.png/) 是没办法修改图片尺寸的，可以使用html中的 <img>标签： 
    <img src="http://xxx.com/xxx.png/" alt="title" width=XXpx height=XXpx> 
    width 和 height 添加想要的尺寸。


##     域名配置

   

###  自己的博客网站就建好了，想要分享出去的小伙伴就要想办法让自己的网页能被百度等搜索引擎搜到，或者这样，百度搜索： site:name.github.io ，出现错误页面就表示搜不到。

    很遗憾，百度是禁止抓取 github pages 的内容的，可以购买一个自己的专属域名，有很多选择，阿里云、腾讯、花生壳域名等，百度站长平台有个链接提交功能，但是它只是加速爬取，并未解决收录：
    ![Image Title](https://img-blog.csdn.net/20180401103839442?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0tOSUdIX1lVTg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

##     总结

    

### Jekyll Writer是一款跨平台的Jekyll网站管理程序，它可以让使用者避免接触Git和Ruby等专业的技术而直接创建和管理基于GitHub Pages的静态网站，同时支持对文章的版本进行管理。Jekyll Writer可以通过jekyllwriter.com进行下载。

    好了，Jekyll不再只是Geek的玩物，大家一起High起来吧！