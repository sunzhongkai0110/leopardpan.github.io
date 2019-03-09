---
layout: post
title: Git命令使用（GitHub篇）
date: 2019-03-09 
tag: Git
---

###  1. 将项目从GitHub克隆到本地：git clone

![](/images/posts/Git/Git1.png)

问题1：当该路径下已经存在与repository同名的文件夹，则会出现如下错误：

![](/images/posts/Git/Git2.png)

解决方法：到该路径下删除或重命名同名文件夹

问题2：执行目录错误，执行目录一定要切换到根目录~

![](/images/posts/Git/Git3.png)

解决方法：切换到根目录  cd~

区别：git clone和git pull

git clone:适用于本地没有repository的情况，将整个repository从GitHub下载下来

git pull:适用于本地有repository的情况，将repository 里更新后数据下载过来，并且与本地代码merge
 
### 2. 进入要push的目标文件夹，右击，打开Git Bash

![](/images/posts/Git/Git4.png)

### 3. 初始化：git init

init后会出现.git隐藏文件夹—本地代码库

![](/images/posts/Git/Git5.png)

### 4. 加载文件：git add .(注意：先空格再键入点.)

![](/images/posts/Git/Git6.png)

### 5. 提交文件，创建时间点：git commit -m “时间点”

![](/images/posts/Git/Git7.png)

### 6. 查看状态：git status

![](/images/posts/Git/Git8.png)

### 7. 推送代码

第一次推送，添加远程的代码库到配置：git remote add origin https://github.com/your repositoryname

![](/images/posts/Git/Git9.png)

问题：如果之前添加过配置，则会出现问题

![](/images/posts/Git/Git10.png)

解决方法：无需添加配置，推送代码即可

推送代码：git push origin master

![](/images/posts/Git/Git11.png)

问题：如果GitHub上repository比本地代码库的代码新，则会出现问题

![](/images/posts/Git/Git12.png)

解决方法：将GitHub上的代码pull下来，在本地修改，再将修改后的代码push到GitHub上

![](/images/posts/Git/Git13.png)

### 参考资料：

Git 中 pull 和 clone 的区别
https://blog.csdn.net/HeatDeath/article/details/79135462

Git之Github使用（一）：Push代码到Github
http://www.cnblogs.com/android-blogs/p/5816833.html

转载请注明：[孙仲锴的博客](https://sunzhongkai0110.github.io) » [Git命令使用（GitHub篇）](---%20layout:%20post%20title:%20Git%E5%91%BD%E4%BB%A4%E4%BD%BF%E7%94%A8%EF%BC%88GitHub%E7%AF%87%EF%BC%89%20date:%202019-03-09%20%20tag:%20Git%20---%20%20###%20%201.%20%E5%B0%86%E9%A1%B9%E7%9B%AE%E4%BB%8EGitHub%E5%85%8B%E9%9A%86%E5%88%B0%E6%9C%AC%E5%9C%B0%EF%BC%9Agit%20clone%20%20!%5B%5D%28/images/posts/Git/Git1.png%29%20%20%E9%97%AE%E9%A2%981%EF%BC%9A%E5%BD%93%E8%AF%A5%E8%B7%AF%E5%BE%84%E4%B8%8B%E5%B7%B2%E7%BB%8F%E5%AD%98%E5%9C%A8%E4%B8%8Erepository%E5%90%8C%E5%90%8D%E7%9A%84%E6%96%87%E4%BB%B6%E5%A4%B9%EF%BC%8C%E5%88%99%E4%BC%9A%E5%87%BA%E7%8E%B0%E5%A6%82%E4%B8%8B%E9%94%99%E8%AF%AF%EF%BC%9A%20%20!%5B%5D%28/images/posts/Git/Git2.png%29%20%20%E8%A7%A3%E5%86%B3%E6%96%B9%E6%B3%95%EF%BC%9A%E5%88%B0%E8%AF%A5%E8%B7%AF%E5%BE%84%E4%B8%8B%E5%88%A0%E9%99%A4%E6%88%96%E9%87%8D%E5%91%BD%E5%90%8D%E5%90%8C%E5%90%8D%E6%96%87%E4%BB%B6%E5%A4%B9%20%20%E9%97%AE%E9%A2%982%EF%BC%9A%E6%89%A7%E8%A1%8C%E7%9B%AE%E5%BD%95%E9%94%99%E8%AF%AF%EF%BC%8C%E6%89%A7%E8%A1%8C%E7%9B%AE%E5%BD%95%E4%B8%80%E5%AE%9A%E8%A6%81%E5%88%87%E6%8D%A2%E5%88%B0%E6%A0%B9%E7%9B%AE%E5%BD%95~%20%20!%5B%5D%28/images/posts/Git/Git3.png%29%20%20%E8%A7%A3%E5%86%B3%E6%96%B9%E6%B3%95%EF%BC%9A%E5%88%87%E6%8D%A2%E5%88%B0%E6%A0%B9%E7%9B%AE%E5%BD%95%20%20cd~%20%20%E5%8C%BA%E5%88%AB%EF%BC%9Agit%20clone%E5%92%8Cgit%20pull%20%20git%20clone:%E9%80%82%E7%94%A8%E4%BA%8E%E6%9C%AC%E5%9C%B0%E6%B2%A1%E6%9C%89repository%E7%9A%84%E6%83%85%E5%86%B5%EF%BC%8C%E5%B0%86%E6%95%B4%E4%B8%AArepository%E4%BB%8EGitHub%E4%B8%8B%E8%BD%BD%E4%B8%8B%E6%9D%A5%20%20git%20pull:%E9%80%82%E7%94%A8%E4%BA%8E%E6%9C%AC%E5%9C%B0%E6%9C%89repository%E7%9A%84%E6%83%85%E5%86%B5%EF%BC%8C%E5%B0%86repository%20%E9%87%8C%E6%9B%B4%E6%96%B0%E5%90%8E%E6%95%B0%E6%8D%AE%E4%B8%8B%E8%BD%BD%E8%BF%87%E6%9D%A5%EF%BC%8C%E5%B9%B6%E4%B8%94%E4%B8%8E%E6%9C%AC%E5%9C%B0%E4%BB%A3%E7%A0%81merge%20%20%20###%202.%20%E8%BF%9B%E5%85%A5%E8%A6%81push%E7%9A%84%E7%9B%AE%E6%A0%87%E6%96%87%E4%BB%B6%E5%A4%B9%EF%BC%8C%E5%8F%B3%E5%87%BB%EF%BC%8C%E6%89%93%E5%BC%80Git%20Bash%20%20!%5B%5D%28/images/posts/Git/Git4.png%29%20%20###%203.%20%E5%88%9D%E5%A7%8B%E5%8C%96%EF%BC%9Agit%20init%20%20init%E5%90%8E%E4%BC%9A%E5%87%BA%E7%8E%B0.git%E9%9A%90%E8%97%8F%E6%96%87%E4%BB%B6%E5%A4%B9%E2%80%94%E6%9C%AC%E5%9C%B0%E4%BB%A3%E7%A0%81%E5%BA%93%20%20!%5B%5D%28/images/posts/Git/Git5.png%29%20%20###%204.%20%E5%8A%A0%E8%BD%BD%E6%96%87%E4%BB%B6%EF%BC%9Agit%20add%20.%28%E6%B3%A8%E6%84%8F%EF%BC%9A%E5%85%88%E7%A9%BA%E6%A0%BC%E5%86%8D%E9%94%AE%E5%85%A5%E7%82%B9.%29%20%20!%5B%5D%28/images/posts/Git/Git6.png%29%20%20###%205.%20%E6%8F%90%E4%BA%A4%E6%96%87%E4%BB%B6%EF%BC%8C%E5%88%9B%E5%BB%BA%E6%97%B6%E9%97%B4%E7%82%B9%EF%BC%9Agit%20commit%20-m%20%E2%80%9C%E6%97%B6%E9%97%B4%E7%82%B9%E2%80%9D%20%20!%5B%5D%28/images/posts/Git/Git7.png%29%20%20###%206.%20%E6%9F%A5%E7%9C%8B%E7%8A%B6%E6%80%81%EF%BC%9Agit%20status%20%20!%5B%5D%28/images/posts/Git/Git8.png%29%20%20###%207.%20%E6%8E%A8%E9%80%81%E4%BB%A3%E7%A0%81%20%20%E7%AC%AC%E4%B8%80%E6%AC%A1%E6%8E%A8%E9%80%81%EF%BC%8C%E6%B7%BB%E5%8A%A0%E8%BF%9C%E7%A8%8B%E7%9A%84%E4%BB%A3%E7%A0%81%E5%BA%93%E5%88%B0%E9%85%8D%E7%BD%AE%EF%BC%9Agit%20remote%20add%20origin%20https://github.com/your%20repositoryname%20%20!%5B%5D%28/images/posts/Git/Git9.png%29%20%20%E9%97%AE%E9%A2%98%EF%BC%9A%E5%A6%82%E6%9E%9C%E4%B9%8B%E5%89%8D%E6%B7%BB%E5%8A%A0%E8%BF%87%E9%85%8D%E7%BD%AE%EF%BC%8C%E5%88%99%E4%BC%9A%E5%87%BA%E7%8E%B0%E9%97%AE%E9%A2%98%20%20!%5B%5D%28/images/posts/Git/Git10.png%29%20%20%E8%A7%A3%E5%86%B3%E6%96%B9%E6%B3%95%EF%BC%9A%E6%97%A0%E9%9C%80%E6%B7%BB%E5%8A%A0%E9%85%8D%E7%BD%AE%EF%BC%8C%E6%8E%A8%E9%80%81%E4%BB%A3%E7%A0%81%E5%8D%B3%E5%8F%AF%20%20%E6%8E%A8%E9%80%81%E4%BB%A3%E7%A0%81%EF%BC%9Agit%20push%20origin%20master%20%20!%5B%5D%28/images/posts/Git/Git11.png%29%20%20%E9%97%AE%E9%A2%98%EF%BC%9A%E5%A6%82%E6%9E%9CGitHub%E4%B8%8Arepository%E6%AF%94%E6%9C%AC%E5%9C%B0%E4%BB%A3%E7%A0%81%E5%BA%93%E7%9A%84%E4%BB%A3%E7%A0%81%E6%96%B0%EF%BC%8C%E5%88%99%E4%BC%9A%E5%87%BA%E7%8E%B0%E9%97%AE%E9%A2%98%20%20!%5B%5D%28/images/posts/Git/Git12.png%29%20%20%E8%A7%A3%E5%86%B3%E6%96%B9%E6%B3%95%EF%BC%9A%E5%B0%86GitHub%E4%B8%8A%E7%9A%84%E4%BB%A3%E7%A0%81pull%E4%B8%8B%E6%9D%A5%EF%BC%8C%E5%9C%A8%E6%9C%AC%E5%9C%B0%E4%BF%AE%E6%94%B9%EF%BC%8C%E5%86%8D%E5%B0%86%E4%BF%AE%E6%94%B9%E5%90%8E%E7%9A%84%E4%BB%A3%E7%A0%81push%E5%88%B0GitHub%E4%B8%8A%20%20!%5B%5D%28/images/posts/Git/Git13.png%29%20%20###%20%E5%8F%82%E8%80%83%E8%B5%84%E6%96%99%EF%BC%9A%20%20Git%20%E4%B8%AD%20pull%20%E5%92%8C%20clone%20%E7%9A%84%E5%8C%BA%E5%88%AB%20https://blog.csdn.net/HeatDeath/article/details/79135462%20%20Git%E4%B9%8BGithub%E4%BD%BF%E7%94%A8%EF%BC%88%E4%B8%80%EF%BC%89%EF%BC%9APush%E4%BB%A3%E7%A0%81%E5%88%B0Github%20http://www.cnblogs.com/android-blogs/p/5816833.html%20%20%E8%BD%AC%E8%BD%BD%E8%AF%B7%E6%B3%A8%E6%98%8E%EF%BC%9A%5B%E5%AD%99%E4%BB%B2%E9%94%B4%E7%9A%84%E5%8D%9A%E5%AE%A2%5D%28https://sunzhongkai0110.github.io%29%20%C2%BB%20%5BGit%E5%91%BD%E4%BB%A4%E4%BD%BF%E7%94%A8%EF%BC%88GitHub%E7%AF%87%EF%BC%89%5D%28https://sunzhongkai0110.github.io/2019/03/Git%E5%91%BD%E4%BB%A4%E4%BD%BF%E7%94%A8-GitHub%E7%AF%87/%29)  

