# Git

#### git clone 和 download zip的区别：

download zip下载解压得到的是文件夹；

 而git clone得到的是仓库；     文件夹通过git初始化（git init）后才能变成仓库。



Git三个概念： 提交commit、仓库repository、分支branch；

<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230608205948624.png" alt="image-20230608205948624" style="zoom:50%;" />



<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230608215620384.png" alt="image-20230608215620384" style="zoom:50%;" />

<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230608215803950.png" alt="image-20230608215803950" style="zoom:50%;" />

---

### 狂神-git

[笔记链接](https://www.kuangstudy.com/bbs/1532247011263672321)

版本控制

本地版本控制

集中式版本控制系统 有SVN

分布式版本控制系统  有git

![image-20230709163702534](C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230709163702534.png)

#### git的必要配置：

​	git config -l 查看配置

​	git config --system --list 查看系统配置

​	git config --global --list 查看用户自己配置

​					（此处的配置文件信息可以在git安装路径下的etc的gitconfig找到）

<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230709170122332.png" alt="image-20230709170122332" style="zoom: 33%;" />

安装git后首先要设置自己的用户名和e-mail地址。因为每次git提交都会使用该信息。它被永远的嵌入到你的提交中

<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230709165139641.png" alt="image-20230709165139641" style="zoom:67%;" />

<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230709165742224.png" alt="image-20230709165742224" style="zoom:67%;" />

此处的配置之后在用户中的.gitconfig文件中可以查看：

<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230709165859671.png" alt="image-20230709165859671" style="zoom:67%;" />



<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230709195914362.png" alt="image-20230709195914362" style="zoom:50%;" />



<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230709200223188.png" alt="image-20230709200223188" style="zoom:67%;" />



#### git基本操作

<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230709201609782.png" alt="image-20230709201609782" style="zoom:50%;" />

提交时忽略文件：

有些时候我们不想把某些文件纳入版本控制中，比如数据库文件，临时文件等；

在主目录下建立”.gitignore”文件，此文件有如下规则：

![image-20230709203140412](C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230709203140412.png)



#### IDE中集成git，并提交到github

(使用的是pycharm)

通过pycharm新建一个工程文件，并把一个空的git clone下的文件复制进来，直接在pycharm中即为git；

git add .

git commit -m "第一次提交"

git push 

#### git分支

<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230709221240118.png" alt="image-20230709221240118" style="zoom:67%;" />

<img src="C:\Users\14704\AppData\Roaming\Typora\typora-user-images\image-20230709221328239.png" alt="image-20230709221328239" style="zoom: 67%;" />





