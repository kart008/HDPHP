#后盾网V5【威武】课堂
###通过Git获得V5代码
> 1. [http://git.oschina.net/houdunwang/v5](http://git.oschina.net/houdunwang/v5) (推荐）  
> 2. [https://github.com/houdunwangxj/v5](https://github.com/houdunwangxj/v5)

##什么是V5
1. 通过V5课堂让后盾网“盾友“”的技术更威武
2. 后盾网国内原创视频最多的培训机构
3. 唯一可以让学习独立完成项目的培训机构
4. 唯一可以教会学习独立写框架的培训机构
5. 唯一有开源高性能框架HDPHP的培训机构
6. 唯一拥有大应用CMS系统的培训机构
7. 后盾网是国内最专一的PHP培训机构，够专业

###技术支持：
>后盾网： [http://www.houdunwang.com](http://www.houdunwang.com "后盾网")
> 
>HDPHP官网： [http://www.hdphp.com ](http://www.hdphp.com "HDPHP官网")
>
![后盾网  人人做后盾](http://www.hdphp.com/houdunwang.jpg)

 
## QQ群
群1:166421499

##V5目录说明
- Doc--文档资料
- Lession--理论课
- Cms--	cms项目

#CMS系统测试  必须先执行v5cms.sql文件
---
>#2014-6-6日
1. 使用hdcms高效的缓存解决大并发问题
2. 如何生成全站静态html文件
3. 网站伪静态设置
##网站迁移
1. 备份数据
2. 将网站文件夹整个FTP到远程服务器
3. 重新安装CMS（删除install/lock.php文件)
4. 更新全站缓存
5. 还原数据


---
>#2014-4-18日
1. HDCMS的安装与基本使用
---

---
>#2014-4-11日
1. CMS安装模块的创建
2. CMS项目完结
---

---
>#2014-4-4日
1. 网站数据备份模块
2. 网站数据还原处理

---

---
>#2014-4-4日
1. 网站数据备份模块
2. 网站数据还原处理

---

---
>#2014-3-28日
1. 内容页字段分配
2. javascript实现点击数
3. 内容页Route配置

---

---
>#2014-3-21日
1. 开发channel模板标签
2. 开发列表页pagelist模板标签
3. 完成首页、列表页、内容页数据分配

---

---
>#2014-3-14日
1. 前台模板目录设计
2. 自定义标签（类似DEDE标签体系,快速开发必备功能）

---

---
>#2014-3-7日
1. 网站配置模块开发

---
>#2014-2-28日
1. 文章编辑操作
2. 网站配置项模块
 
---
>#2014-2-21日
1. 文章发表操作
2. 快速调用UEDITOR编辑器调用

------
>#2014-1-17日
1. 栏目表设计
2. 网站无限级栏目
3. 文章表设计 
4. 扩展模型自动验证、自动完成实例操作
5. 使用HDJS完成自动Ajax提交

预习说明：
把HDJS手册都打一遍，把HDPHP中关于自动验证、自动完成的部分看一下

------

>#2014-1-10日
1. 使用HDJS快速完成自动验证
2. 项目的应用组部署
3. V5CMS后台登录操作
4. 作业：通过HDPHP结合HDJS(自动验证）完成CMS系统的登录操作

------
> #2014-1-3日
1. 隐藏index.php
2. URL伪静态设置
3. URL路由定义
4. 扩展模型的基本使用
5. 作业安排
```
1. 创建应用  TEST
2. 连接数据
3. 创建一个用户表
4. 实现路由策略：
localhost/v5/3/houdunwangxj => localhost/v5/3/index.php/User/show/username=houdunwangxj
```

####课前预习
1. 预习前2堂课讲的知识
2. 看一下后盾网论坛的正则表达式视频教程

#### 使用软件
- Wamp Navicat Sublime
- Navicat 下载地址： http://www.xiazaiba.com/html/1846.html

----
> #2013-12-27日 第2课
 
1. 连接数据库
2. 使用HDPHP模板引擎
3. 完成数据的CURD
4. 文章发表操作
5. 文章查询分页操作
6. 作业安排

------
> #2013-12-20日 第1课

##课程安排



####本节课程需要到软件
Wamp

```
下载地址：http://www.wampserver.com/en/
```

Sublime Text

```
下载地址：http://www.sublimetext.com/
```

GitHub for windows


```
1. 下载地址：http://windows.github.com/
```

GitHub for windows安装

```
1. 在github.com上注册帐号
2. 通过360软件管理等平台安装,microsoft.net framework 4.5
2. 下载软件http://windows.github.com/
3. 双击安装
4. 安装后启动github for windows
5. 点击log in,使用github帐号登录
```
MsysGit


```
下载地址：http://msysgit.googlecode.com/files/Git-1.8.4-preview20130916.exe
```

MarkdownPad

```
下载地址：http://www.markdownpad.com/
```
####Git介绍
1. Git是目前世界上最先进的分布式版本控制系统
2. 可以记录每一次我们的代码改动
3. 当我们想回到曾经的代码状态时，git会做到
4. 分支更快、更容易。
5. 支持离线工作；本地提交可以稍后提交到服务器上
6. 有别于svn，Git是分布式版本控制系统


####集中版本控制
* 集中式版本控制系统，版本库是集中存放在中央服务器的
* 先从中央服务器取得最新的版本，然后才可以工作
* 要再把自己的代码推送给中央服务器
* 集中式版本控制系统必须联网才能工作。

####分布式版本控制
* 分布式版本控制每个人的电脑上都是一个完整的版本库
* 不需要联网也可以进行版本控制
* 因为每个人电脑都有一套版本库，安全性更高
* 更方便快速的分支管理
 
####分支branch


如果有一个正在运行的项目比如hdphp,如果我们给项目增加一个新功能，如果每天都提交新代码，由于新功能的代码还没有写完，会造成原来正常运行的hdphp都不可以运行。
这时我们可以创建一个版本新分支，在这个新分支上工作。好处是不破坏master主分支。而且我们鼓励使用Git的分支功能。


####获得HDPHP项目
####使用GitHub for windows获得
1. 下载GitHub for windows(下载过程可能会中断，多试几次就可以了)
2. 打开网址https://github.com/houdunwangxj/hdphp
3. 点击“Clone in Desktop“”按钮,这时会自动通过git for windows 软件下载hdphp项目

####使用MsysGit
1. 下载安装MsysGit
2. 使用

####作业
1. 下载安装GitHub for windows
2. 通过GitHubforwindow 下载hdphp与v5
3. 通过hdphp创建admin应用与index应用
4. 创建属于你自己的项目（项目名称自己命名）

