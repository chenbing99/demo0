# 第一节课
### 1.github是什么
 
   是一个面向开源及私有软件项目的托管平台`（IT技术人员的社交平台）`
   
### 2.git是什么
 
   版本控制系统`（版本控制系统还有svn等）`
   
### 3.学习github的5个理由
1. 有很多很厉害的技术人员，称大牛，比如百度、阿里等等
2. 可以接触到最新和最前沿的IT技术，我们可以接触到这些 软件的初始、中间以及最终状态，可以第一时间了解到软件 产品的发展动向，同时能够清楚地了解到时下最火热最具有 发展力的技术。
3. 我们可以学到开发语言、项目流程、设计思想、编码规范 等等，同时可以记录我们技术的发展，像社交网站中的一个 时间轴，我们可以随时去看自己的学习历程以及积累，有时 还会发现自己的不足之处，进而改正进步。
4. github是一个开源的，所有项目的代码文档对我们都是开 放的。在上面我们可以找到一些项目参与其中，增加自己的 项目实战经验，为以后找工作和做项目做铺垫。
5. 在github上有一些教程，我们可以进行学习，优质的学习 资源非常丰富。
### 4.github的优势是什么
1. 只支持Git作为唯一的版本库格式进行托管
2. 完整协议支持（http:ssh协议）
3. 在线文件编辑
4. 社交网络元素
5. 特色工作模式（逐行批注）
6. 私有仓库托管
7. Ruby On Rails（架构）

### 5.通过github年度报告让你记忆最深刻的信息有哪些
>当前最受欢迎的语言是javascript；java语言排行第二

### 6.github上有可以个人账号 还可以有`（组织）`账号

### 7.github上面的两个组成要素是什么
   仓库/项目 人/组织


### 8.github上两个重要页面
   个人主页  数字仪表版
  
### 9.主页菜单都包含什么
   Overview  Repositories  Stars  Followers  Followling

### 10.仓库的心跳线代表什么
   Pulse（Pulse是体现该仓库软件开发活跃度的功能）
### 11.star的作用是？
   star 的作用是收藏项目，目的是方便以后查找。

### 12.fork的作用是？
   fork 的作用是参与项目，目的是你增加新的内容，然后 Pull Request，把你的修改和主仓库原来的内容合并。
### 13.watch的作用是？
   watch 的作用是关注项目，目的是等作者更新的时候，你可以收到通知。

### 14.搜索结果分别有哪些类别
   Repositories   Code  Commits  Issues   Wikis   Users
### 15.你在github上挖到什么宝
* 大牛和项目
* <Node.js 包教不包会>-by alsotang 
* jstraining  RuanYiFeng

# 第二节课
### 1.个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？

>New repository  Import repository   New gist       New organization 
  
>新建仓库         导入仓库           创建代码片段   创建组织 
### 2.如何能将仓库中的html文件直接解析成页面？

  Settings->将默认的None改为master branch->Save
### 3.如何删除仓库

  Settings->Delete this repository->写上仓库名字->确认删除
### 4.Bash是什么操作系统的命令?

Linux系统
### 5.Pwd是什么命令?

打印当前工作目录
### 6.Cd是什么命令?

改变目录(Cd+目录)
### 7.Echo是什么命令?

打印内容(Echo+"内容")
### 8.配置git用户名的命令

git config --global user.name "用户名"
### 9.配置邮箱的命令

git config --global user.email "邮箱"
### 10.命令行换行方式：`\`
### 11.命令行终结方式：`ctrl+c`
### 12.使用命令行比GUI方式有何优势

1. 比GUI的效率高
2. github提供的功能有限 
3. github只能局限于创建文件、编辑几个文件，无法创建文件夹
4. 在github上不能对多个文件进行同时编辑
### 13.提交到本地仓库时为什么有暂存区
1. workspace中可能会有好多编辑，可以将所有编辑同时提交到index中，而从 index提交到repository时，可以将灵活的将编辑内容进行提交；
2. 回撤时变动的影响是不同的，范围是不一样的；
3. 在进行commit提交时，可以控制提交的颗粒度
### 14.新建代码仓库的命令

   git init
### 15.git clone [url] 这个命令的作用是

   下载一个项目和它的整个代码历史
### 16.添加指定文件到暂存区的命令

   git add [file1][file2]
### 17.删除工作区文件，并且将这次删除放入暂存区的命令

   git rm [file1][file2]
### 18.改名文件，并且将这个改名文件放入暂存区的命令

   git mv [file-origin] [file-renamed]
### 19.提交暂存区到仓库的命令

   git commit -m [message]
### 20.直接从工作区提交到仓库的命令
   
   git commit -a -m [message] #前提是该文件已经有仓库中的历史版本
### 21.显示变更信息的命令
   
   git status
### 22.查看历史信息的命令
   
   git log
### 23.Commit的意义是
   
   提交
### 24.Pull的意义是
   
   将远程仓库的提交拉下到本地
### 25.Push的意义是
   
   将本地的提交推送到远程仓库 

# 第三节课：
### 1.MarkDown是什么？

>Markdown是一个web上使用的文本到HTML的转换工具，可以通过简单、易读易写的文本格式生成结构化的HTML文档
  
>Github，Stackoverflow，有道云，思维导读等网站均支持这种格式
### 2.MarkDown的特点？
  
>兼容HTML 在线观看 平台支持 排版样式简单
### 3.MarkDown的用途？
  
>IT人士：写日志、技术文稿、记录代码片段、撰写文档
### 4.MarkDown的编辑工具有哪些？
  
>Mac OS:MOU
  
>Windows：MarkDown Pad,Mark Pad,HBuilder...
  
>Linux:ReText
  
>Web:GitHub,markable.in（在线编辑）,有道云笔记
### 5.MarkDown的区块元素和区段元素分别包含哪些？
  
#### 区块元素：

* 段落和换行
* 标题
* 区块引用
* 列表
* 代码区块
* 分割线
  
#### 区段元素：
* 链接
+ 强调
- 代码
+ 图片
