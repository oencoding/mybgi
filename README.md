# 基于Django的个人网站   

本项目为一个基于Django的个人网站，项目部署在阿里云，欢迎访问：[明月不归尘](https://fslong.xyz)，计划的特性有：   
## (一)、博客部分 
1. 主题可定制、更换（心情不好就换个主题，但不需要重新设置models）；
2. 快速搭建博客，能让只有几小时Python基础的小伙伴也快速上手；
3. Views与APP分离，将Views置于主题中，便于维护管理；  
## (二)、 WebAPPs部分  
1. 主要是平时写的一些小型程序归类，以此来记录学习历程，其中包括比如爬虫、api等；
2. 万一有小伙伴需要，也可在此处查找使用；  

这是作为一个初学者新建的坑，主要是想把学到的东西想方设法放到实际项目中从而加深记忆与提高技能。  
目前还是很原始，很基础的版本，陆续完善中，其中参考了hexo搭建的博客的效果，特此感谢[yilia](https://github.com/litten/hexo-theme-yilia.git) 。  
希望各位大佬轻喷，如果有啥建议给我发邮件或者加我QQ：470657570，谢谢！  

## 一、To do list:
√ 1. 编写日志页面；  
√ 2. 编写管理日志页面；  
√ 3. 注册及登陆页面；  
√ 4. 评论；  
▢ 5. 增加导入一键markdown文件功能；   
▢ 6. WebAPPs的开发；  
▢ 6. 未完待续...  
## 二、以下是开发日志，倒序书写：
### 2018.07.24
1. pyspider初识；
2. wordcloud初识；
### 2018.07.24
1. win4000数据爬取；
### 2018.07.23
1. netbian数据爬取；
### 2018.07.20
1. 修改个人头像位置；
### 2018.07.19
1. 建立框架初步完成，后面就是完善详细内容的事情了；
2. 加入个人简历的连接；
### 2018.07.12
1. 这两天忙着写简历（另外一个坑[An online resume frame by Pyrhon+jQuery+UIkit. ](https://github.com/fslong520/pju-resume)）以及考科目四，可能更新不及时，见谅！  
### 2018.07.12
#### (二)、博客开发
1. 新增博文一篇(其实是昨天的)；
2. 增加搜索功能(支持标题和全文同时检索);
### 2018.07.11
1. 继续学习MySQL，终于弄明白如何配置了，晚上写教程;
2. 编写完MariaDB安装配置教程，修复首页一个小的bug；
### 2018.07.10
1. 使用scrapy重写kgbook爬虫；
2. 正式开始学习MySQL;
### 2018.07.08
1. 第一个scrapy爬虫；  
### 2018.07.07
1. 第一个使用pyqt5的爬虫；
### 2018.07.06
1. 科目三过了，把昨晚最后写的小程序推送下。
### 2018.07.05
1. 练车有点心累，也没想好下一步做啥子，今天就随便推送一下子。
### 2018.07.04 
#### (一)、WebAPP开发
1. 修改标题栏，然后装了个pycharm玩玩！，
### 2018.07.03 
#### (一)、WebAPP开发
1. 在练科三，太累了，就把爬完的数据统计一下放在了网站上，用进度条显示；
### 2018.07.02 
#### (一)、WebAPP开发
1. 在练科三，太累了，就把爬完的数据以及优化过的代码推送一下吧；
### 2018.07.01 
#### (一)、WebAPP开发
1. 编写爬虫，获取电子书数据；
### 2018.06.30  
#### (一)、WebAPP开发
1. 测试视频接口，删除不能用的，修改有问题的；
### 2018.06.29
新的学习目标，参考自：[听说你想学习爬虫？送你一本葵花宝典！不用自宫！高效的学习路径](http://www.qingpingshan.com/jb/python/389270.html)：  
1. 了解爬虫的基本原理及过程
2. Requests+Xpath 实现通用爬虫套路
3. 了解非结构化数据的存储
4. 学习scrapy，搭建工程化爬虫
5. 学习数据库知识，应对大规模数据存储与提取
6. 掌握各种技巧，应对特殊网站的反爬措施
7. 分布式爬虫，实现大规模并发采集，提升效率
### 2018.06.28
#### (一)、WebAPP开发
1. 增加一堆视频解析接口；
2. 修改目录菜单；
3. 修改通知消息；
### 2018.06.27
#### (一)、WebAPP开发
1. 判断ip地址所在区域展示天气信息；
2. 增加目录；
3. 更换接口；
#### (二)、博客开发
1. 新增博文一篇；
2. 修改首页效果；
### 2018.06.26
#### (一)、WebAPP开发
1. 增加解析视频功能（某某vip视频接口）；
### 2018.06.25
#### (一)、WebAPP开发
1. 天气卡片完成；
2. 将天气信息，bing美图封装成api；
3. 设置使用git将代码部署到服务器上(再测试一次，再再测试一次，再再再测试一次，最后测试一次，还是有问题唉！)；
4. 终于成功了，原来是远程服务器上脚本执行权限的问题，另外如果要推送代码到多个仓库，其实只需要在git下面的config里的origin分支加一行`url=<sshAdress>`即可一键推送；
5. 根据ip查询位置；
### 2018.06.22  
1. 修改跳转用的主页
2. 开新坑：WebAPPs；
    a. 获取指定日期必应美图卡片； 
    b. 天气卡片占位；
### 2018.06.21  
1. 完成博客的增删改，查就等会;
2. 完成了账户信息的修改；
3. 基本功能已经完成；
### 2018.06.20
1. 部署到了阿里云，欢迎访问：[明月不归尘](https://fslong.xyz) ；
2. 编写用户管理页；
3. 加入使用Ajax验证账户密码；
4. 由于django使用了csrf_token，用Ajax直接发送post请求会被拒绝，因此需要在使用Ajax之前加入以下代码（不能在文件中，必须在要使用Ajax的地方）：  
```javascript
$.ajaxSetup({
    data: {
        csrfmiddlewaretoken: '{{ csrf_token }}'
    },
});
```
### 2018.06.18
1. 完成了登陆和注册页面；
2. 完成了发表评论和显示评论；
3. 继续完善models和写完的页面；
### 2018.06.13  
1. 完善了博客编辑页面，增加了富文本编辑器；  
2. 完善了注册及登陆页面模板；  
3. 将登陆界面放在弹出框里面；  
### 2018.06.10  
最近在考驾照，推送时间不定，各位见谅。
1. 继续完善models；
2. 继续完善views；
3. 继续完善admin；
4. 总之就是东写一下西写一下，是时候建立一个To do list了！
### 2018.06.07
1. 将代码托管到Github上，开启交友之旅！