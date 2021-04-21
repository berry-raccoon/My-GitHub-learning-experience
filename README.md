# My-GitHub-learning-experience
2021/4/20  
# 一、 学习契机
之前有听过GitHub,也接触过一些大佬提供在GitHub上的代码。前几天我写了一个很长的代码，不知道存放在哪里的时候，我就想到了GitHub，因此首先下载了一本GitHub的电子书《GitHub入门与实践》，开始了学习之旅。  
GitHub可能出现登不上去的情况，可以参考两个网址：  
[1. GitHub上不去的问题解决(csdn)](https://blog.csdn.net/weixin_44411398/article/details/112510646?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522161882963416780366548280%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=161882963416780366548280&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-112510646.pc_search_result_no_baidu_js&utm_term=github%E4%B8%8A%E4%B8%8D%E5%8E%BB)  
[2. 解决浏览器打不开github网站常用方法(csdn)](https://blog.csdn.net/sanyang730/article/details/82258202?utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-2.control&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromMachineLearnPai2%7Edefault-2.control)

# 二、 写作目的
## 1. 记录学习过程  
之前以为GitHub只是类似一个博客一样的网站，但看了电子书后，感觉里面的东西较多也比较复杂，因此我把自己的入门经历记录下来，方便以后回顾，也对一些从来没有接触过GitHub的小白作为一个参考。
## 2. 练习使用   
在完成这篇文章的过程，包含从账号的注册，到Git仓库的使用，以及下载GitHub客户端，体验GitHub相应的功能。
## 3.学习MarkDownPad2 
之前在csdn、百度脑图上也接触过MarkDown，不过之前下了MarkDownPad2软件只是作为浏览使用，这次使用MarkDownPad2主动编写文档。

# 三、 学习过程
## 1.	新手入门教程  
注册完账号之后，点着点着就点到了一个网址[What do you want to do first?](https://github.com/join/get-started)，里面有很多指导课程，我选的是`“Introduction to GitHub”`。课程内容为主要带你走一遍最基本的使用，全英文的教程读起来稍微有点吃力，学完教程后仍就是云里雾里。
## 2. 知乎
在知乎上关注的问题是[如何使用 GitHub？](https://www.zhihu.com/question/20070065?sort=created)，里面的答者也是从最基本的操作开始介绍的，包括下载客户端进行编辑，另外有一位小姐姐的回答，更是介绍了GitHub多元化的使用。
## 3. 《GitHub入门与实践》
在看完前面的内容后，再看这本书就容易了那么一点点，书本的学习可以让你学一样东西更加系统，但是我目前也只是看了最基本的操作，自己编辑和看别人代码为主，比如如何在团队中使用等还没有接触。书中的大部分操作都是在安装Git下完成的，类似于输入命令行，但现阶段我更倾向于图形化的操作，学习Git命令行可以参考网站[Learn Git Branching](https://learngitbranching.js.org/?locale=zh_CN)。
## 4. MarkDownPad2使用
MarkDownPad2与csdn的MarkDown编辑器存在着略微的差异。我看了一个官方的文档，点击Help - Documentation - [Standard MarkDown Syntax Guild](https://daringfireball.net/projects/markdown/syntax)。我的学习方法是把里面的内容复制到MarkDownPad2中，对应着右边的预览，边看边尝试。  
笔记链接：My-GitHub-learning-experience/MarkdownPad2使用指南.pdf
## 5. 其他学习网站
[(1)GitHub.com中文指导网站](https://docs.github.com/cn/github)
[(2)GitHub.com同款英文指导网站](https://docs.github.com/en/github/writing-on-github/organizing-information-with-tables)
# 四、 知识点
## 1. 下载GitHub客户端
[下载客户端](https://desktop.github.com/)一是因为GitHub的连接不稳定，二是因为包含了网页版的基本功能，如分支创建，记录修改过程，上传，更新等。界面简单干净，因此决定使用，尤其是以后打算写论文，本地的doc文件不香嘛。网站上的修改或上传，可以点击客户端的fetch或pull实现同步，不过速度有点慢。
## 2. Git仓库
首先要知道Git仓库和GitHub的区别：GitHub包含Git仓库，在此阶段的学习，也是围绕Git仓库展开。包括仓库的创建等，书P31有介绍。
## 3. 分支
分支是原内容的一个拷贝。可以实现一个不同版本的创作，没有一个新的版本，你就创建一个分支，如果你想回到上一个版本，找到那个分支就可以了。

- 创建 [分支](https://blog.csdn.net/qq_30607843/article/details/84404000?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522161891506916780265487756%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=161891506916780265487756&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_v2~rank_v29-2-84404000.pc_search_result_no_baidu_js&utm_term=github%E5%90%88%E5%B9%B6%E5%88%86%E6%94%AFi) 
- 合并分支  
	找到要合并的分支，选择Compare & pull request，再comfirm merge，就可以看到main分支的内容被更新。此外如果要删除分支，可以点击库首页的branches，删除即可。
	2021/4/20接触了一个新的名词**git rebase**，具体是啥还不明白。
- 擅于利用分支  
	给别人pull request，以及自己创作的时候都可以用到分支，分支也是GitHub的一个特色。
## 4. Pull Request
Pull Request是用户修改代码后向对方仓库发送采纳请求的功能。详细的Pull Request在书中P118页有介绍，大致步骤为： fork -> 创建分支 -> 发送Pull Request请求。
## 5. 页面认识
- 大佬的页面  
书P77 
- 仓库管理  
书P80  
删除仓库：在仓库页面的Settings下拉的Danger Zone就可以删除仓库。
# 五. 后续学习
2021/4/21
## 1. TaskList
- [x] A
- [ ] B
## 2. table

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
## 3. Wiki
