---
layout: post
title: Git命令使用（GitHub篇）
date: 2019-03-08 
tag: Git
---

###  1. 将项目从GitHub克隆到本地：git clone

![此处输入图片的描述][1]

问题1：当该路径下已经存在与repository同名的文件夹，则会出现如下错误：
![此处输入图片的描述][2]
解决方法：到该路径下删除或重命名同名文件夹

问题2：执行目录错误，执行目录一定要切换到根目录~
![此处输入图片的描述][3]
解决方法：切换到根目录  cd~

区别：git clone和git pull
git clone:适用于本地没有repository的情况，将整个repository从GitHub下载下来
git pull:适用于本地有repository的情况，将repository 里更新后数据下载过来，并且与本地代码merge


 
### 2. 进入要push的目标文件夹，右击，打开Git Bash

![此处输入图片的描述][4]

### 3. 初始化：git init
init后会出现.git隐藏文件夹—本地代码库

![此处输入图片的描述][5]

### 4. 加载文件：git add .(注意：先空格再键入点.)

![此处输入图片的描述][6]

### 5. 提交文件，创建时间点：git commit -m “时间点”

![此处输入图片的描述][7]

### 6. 查看状态：git status

![此处输入图片的描述][8]

### 7. 推送代码
第一次推送，添加远程的代码库到配置：git remote add origin https://github.com/your repositoryname

![此处输入图片的描述][9]

问题：如果之前添加过配置，则会出现问题
![此处输入图片的描述][10]
解决方法：无需添加配置，推送代码即可

推送代码：git push origin master

![此处输入图片的描述][11]

问题：如果GitHub上repository比本地代码库的代码新，则会出现问题
![此处输入图片的描述][12]
解决方法：将GitHub上的代码pull下来，在本地修改，再将修改后的代码push到GitHub上
![此处输入图片的描述][13]

参考资料：
Git 中 pull 和 clone 的区别
https://blog.csdn.net/HeatDeath/article/details/79135462
Git之Github使用（一）：Push代码到Github
http://www.cnblogs.com/android-blogs/p/5816833.html

转载请注明：[孙仲锴的博客](https://sunzhongkai0110.github.io) » [Git命令使用（GitHub篇）](https://sunzhongkai.github.io/2019/03/Git命令使用（GitHub篇）/)  


  [1]: https://graph.baidu.com/resource/101a74356bb2d62991c9a01552050478.jpg
  [2]: https://graph.baidu.com/resource/10110749b3850753ae17401552050803.jpg
  [3]: https://graph.baidu.com/resource/101c14f207b2ead6e8d3c01552050889.jpg
  [4]: https://graph.baidu.com/resource/10101973ecf417f428a2301552051045.jpg
  [5]: https://graph.baidu.com/resource/10138d04b854b28082f1801552052275.jpg
  [6]: https://graph.baidu.com/resource/1012dfb07328448b7997e01552052368.jpg
  [7]: https://graph.baidu.com/resource/10133b9761cb330a0cce501552052550.jpg
  [8]: https://graph.baidu.com/resource/101864814a0a27012524b01552052617.jpg
  [9]: https://graph.baidu.com/resource/1012a1f1295faea0a98c201552052808.jpg
  [10]: https://graph.baidu.com/resource/101a0a3bb16cf88594e6c01552053251.jpg
  [11]: https://graph.baidu.com/resource/10169e4aec6b12612ae3001552053353.jpg
  [12]: https://graph.baidu.com/resource/101a0aa061822a11b235f01552053391.jpg
  [13]: https://graph.baidu.com/resource/101169b73e9849975439401552053429.jpg