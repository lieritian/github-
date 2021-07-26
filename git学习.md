# github学习，git使用

## 一.git学习，借助github托管项目代码

### 1基本概念

仓(Repository)
仓库用来存放项目代码，每个项目对应一个仓库，多个开源项目则有多个仓库

### 2.收藏（Star）

仓库主页star按钮，意思为收藏项目的人数，在GitHub上如果你有一个项目获得100个star都算很不容易了！

### 3.复制克隆项目（Fork）

这个不好翻译，如果实在要翻译我把他翻译成分叉，什么意思呢？你开源了一个项目，别人想在你这个项目的基础上做些改进，然后应用到自己的项目中，这个时候他就可以Fork你的项目（打开项目主页点击右上角的fork按钮即可） ，然后他的GitHub主页上就多了一个项目，只不过这个项目是基于你的项目基础（本质上是在原有项目的基础上新建了一个分支） ，他就可以随心所欲的去改进，但是丝毫不会影响原有项目的代码与结构。

该fork的项目是独立存在的

![image-20210721210736686](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210721210736686.png)

![image-20210721211233256](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210721211233256.png)

![image-20210721211436473](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210721211436473.png)

接收方：

![image-20210721211743164](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210721211743164.png)

![image-20210721200138142](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210721200138142.png)

看自己的收藏

![image-20210721200551464](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210721200551464.png)

![image-20210721201011699](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210721201011699.png)

### 4.发起请求（Pull Request）

发起请求，这个其实是基于Fork的，还是上面那个例子，如果别人在你基础上做了改进，后来觉得改进的很不错，应该要把这些改进让更多的人收益，于是就想把自己的改进合并到原有项目里，这个时候他就可以发起一个Pull Request （简称PR） ，原有项目创建人，也就是你，就可以收到这个请求，这个时候你会仔细review他的代码，并且测试觉得oK7，就会接受他的PR，这个时候他做的改进原有项目就会拥有了。

### 5.关注（Watch）

这个也好理解就是观察，如果你Watch了某个项目，那么以后只要这个项目有任何更新，你都会第一时间收到关于这个项目的通知提醒

![image-20210721201527917](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210721201527917.png)



### 6.事务卡片（Issue）

发现代码BUG，但是目前没有成型代码，需要讨论时用；
问题的意思，举个例子，就是你开源了一个项目，别人发现你的项目中有bug，或者哪些地方做的不够好，他就可以给你提个issue ，即问题，提的问题多了，也就是1ssues ，然后你看到了这些问题就可以去逐个修复，修复ok了就可以一个个的close掉

![image-20210721194340655](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210721194340655.png)

![image-20210721194951313](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210721194951313.png)

### 7.Github主页

账号创建成功或点击网址导航栏github图标都可进入github主页：该页左侧主要显示用户动态以及关注用户或关注仓库的动态；右侧显示所有的git库

### 8.仓库主页

仓库主页主要显示项目的信息，如：项目代码，版本，收藏/关注/fork情况等

### 9.个人主页

个人信息：头像，个人简介，关注我的人，我关注的人，我关注的git库，我的开源项目，我贡献的开源项目等信息、

## 二、github使用

### 1.网址：https://github.com/![800b506b6a699928abd4f5b2dad9011](C:\Users\高旭东\Desktop\800b506b6a699928abd4f5b2dad9011.png)2.github的服务器在国外所有访问比较慢，或者干脆无法访问，就需要翻墙

### 3.shadowsocks在git上搜索，国外的vpn

### 4.giehub上直接编辑文件跟删除文件

![image-20210720163702075](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210720163702075.png)

### 5.删除文件

![image-20210720164331686](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210720164331686.png)

![eb8a3cadb09a2f9df5432e6e177162b](C:\Users\高旭东\Desktop\eb8a3cadb09a2f9df5432e6e177162b.png)

### 6.被删除的文件如何查看

![image-20210720170010732](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210720170010732.png)

### 7.上传文件

![image-20210720172056338](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210720172056338.png)

![image-20210720172355753](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210720172355753.png)

主页

![image-20210721195403100](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210721195403100.png)

### 8.开源项目

1.开源项目贡献流程

1)新建Issue

提交使用问题或者建议或者想法

2) Pull Request

步骤：

1、 fork项目

2、修改自己仓库的项目代码

3、新建pull request

4、等待作者操作（）

## 三、git的安装跟应用

## 1.目的

通过git管理github托管项目代码

### 2.下载安装

1) Git官网下载: https://www.git-scm.com/download/win

git的安装：

![image-20210722104621793](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722104621793.png)

检验是否安装成功



![image-20210722110752065](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722110752065.png)

### 3.git工作区域

![image-20210722112442170](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722112442170.png)

![image-20210722112944529](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722112944529.png)

### 4.Git初始化及仓库创建和操作

基本信息设置

 1．设置用户名

git config  --global user.name 'lieritian'

 2．设置用户名邮箱

git config --global user.email '1023220623@qq.com'

![image-20210722115123453](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722115123453.png)

脚下留心：该设置在github仓库主页显示谁提交了该文件

### 5.初始化，进入需要进入的文件通过以下命令进行初始化：

```git
git init
```

![image-20210722142151857](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722142151857.png)

![image-20210722144343823](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722144343823.png)

![image-20210722144607534](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722144607534.png)

git add .   可以将所有的文件都添加到暂存区

![image-20210722145240462](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722145240462.png)

git commit -m "将文件从暂存区提交到仓库"

### 6.修改文件

也是需要先用git add .来添加，通过git status来看，用git commit -m “”提交

### 7.删除仓库

![image-20210722150325875](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722150325875.png)

### 8.git远程仓库管理

![image-20210722151003001](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722151003001.png)

![image-20210722151124822](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722151124822.png)

git克隆操作

1.将远程仓库github对应的项目复制到本地

```
git clone 仓库地址
```

 git config --list   可以看信息清单

vim  .git/config  通过这个可以看报错

```shell
报错或没有权限

The requested URL returned error: 403 Forbidden while accessing

答案：私有项目，没有权限，输入用户名密码，或者远程地址采用这种类型：

vi .git/config
#将
remote "origin"
url = https://github.com/用户名/仓库名.git 修改为:
#修改为：
remote "origin"]
url = https://用户名:密码@github.com/用户名/仓库名.git
```

## 四、错误问题

### 1.git操作及fatal: Authentication failed for错误解决

1、配置用户信息

git config --global user.name [username]

git config --global user.email [email]

### 2、查询用户信息

git config --list

### 3、如果push遇到在输入密码是熟错后，就会报这个错误fatal: Authentication failed for

解决办法：

git config --system --unset credential.helper

之后你在push就会提示输入名称和密码

git remote  -v 可以显示他的远程仓库

## 五、github pages 搭建个人网站

![image-20210722183545959](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722183545959.png)

![image-20210722181231150](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722181231150.png)

![image-20210722181739801](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722181739801.png)

![image-20210722181831127](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722181831127.png)

![image-20210722181908886](C:\Users\高旭东\AppData\Roaming\Typora\typora-user-images\image-20210722181908886.png)

脚下留心

1， github. pages仅支持静态网页

2、仓库里面这能是.html文件

Project Pages项目站点

https：//用户名.github.io/仓库名

搭建步骤

1）进入项目主页，点击settings

2）在settings页面，点击【Launch automatic page generator 】来自动生成主题页面3）新建站点基础信息设置

4）选择主题5）生成网页

## 六、git命令速查

### 1.查看本地所有的分支

```shell
git branch #查看本地所有分支
git branch -a #查看所有的分支
git branch -r #查看远程所有分支
git branch branch_0.1 master 从主分支master创建branch_0.1分支
git branch -m branch_0.1 branch_1.0 将branch_0.1重命名为branch_1.0
//
git branch 删除远程branch
git push origin :branch_remote_name
git branch -r -d branch_remote_name
//
删除feature1分支： 
$ git branch -d feature1 
```

### 2.查看当前状态

```shell
git status #查看当前的状态
```

### 3.提交

```shell
git commit -m "comment"  #将暂存区的修改提交到仓库 后面添加上有意义的注视信息 
git commit -a #提交当前repos的所有的改变
git commit -v #当你用－v参数的时候可以看commit的差异
git commit -m "This is the message describing the commit" #添加commit信息
git commit -a  #-a是代表add，把所有的change加到git index里然后再commit
git commit -a -v 一#般提交命令
```

### 4.显示所有的远程仓库

```shell
git remote -v #显示所有远程仓库
git remote add origin git@192.168.1.119:ndshow
git remote show #查看远程库
```

### 5.初始化一个git仓库

```shell
git init 
```

### 6.将所有修改添加到暂存区 

```shell
git  add .
```

### 7.比较文件的不同  

```shell
git diff  file   #在file被修改了还未提交的时候查看修改的部分,命令比较文件的不同，即比较文件在暂存区和工作区的差异。
```

### 8.回退之前的版本

```shell
git reset HEAD^            # 回退所有内容到上一个版本  
git reset HEAD^ hello.php  # 回退 hello.php 文件的版本到上一个版本  
git reset  052e           # 回退到指定版本
HEAD 说明：
HEAD 表示当前版本
HEAD^ 上一个版本
HEAD^^ 上上一个版本
HEAD^^^ 上上上一个版本
以此类推...
可以使用 ～数字表示
HEAD~0 表示当前版本
HEAD~1 上一个版本
HEAD^2 上上一个版本
HEAD^3 上上上一个版本
Git的版本回退速度非常快，因为Git在内部有个指向当前版本的HEAD指针，当你回退版本的时候，Git仅仅是把HEAD从指向append GPL 
```

### 9.将文件推送到服务器

```shell
git push origin master #将文件给推到服务器上 
git push origin master:develop
git push origin master:hb-dev #将本地库与服务器上的库进行关联 
```

### 10.切换到远程分支

```shell
git checkout --track origin/dev #切换到远程dev分支
git checkout -b dev #建立一个新的本地分支dev
git checkout dev #切换到本地dev分支
git checkout branch_1.0/master 切换到branch_1.0/master分支
```

### 11.删除本地库

```shell
git branch -D master develop #删除本地库develop
```

### 12.查看git的commit信息

```shell
git log  #查看git的commit信息,每次提交的信息包括注视在内,从最新提交到最久提交 
git log --pretty=oneline   #将commit 信息简化成一行显示 
```

### 13.合并分支

```shell
git merge origin/dev #将分支dev与当前分支进行合并
```

### 14.git中删除指定文件

```shell
git rm 文件名(包括路径) #从git中删除指定文件
```

### 15.从服务器上将代码给拉下来

```shell
git clone git://github.com/schacon/grit.git  #从服务器上将代码给拉下来
```

### 16.看所有的用户

```shell
git config --list  #看所有用户
```

### 17.将文件给push到一个临时空间中

```shell
git stash push #将文件给push到一个临时空间中
git stash pop #将文件从临时空间pop下来
```

### 18.将代码传到服务器上

```shell
git pull #本地与服务器端同步
git push origin master #将本地项目给提交到服务器中
```

### 19.拉取远程最新版到本地

```shel
git fetch #相当于是从远程获取最新版本到本地，不会自动merge
```

### 20.标签

```shell
标签一般打在master分支上 
$ git tag v1.0  // 在当前版本HEAD上打一个名称为v1.0 的标签 
$ git tag   // 查看所有标签,会列表出所有的标签名 
$ git tag v0.8 59bc1cb // 为commit id 为59bc1cb...的commit打上v0.8 标签 
标签不是按时间顺序列出，而是按字母排序的。可以用git show <tagname>查看标签信息 
还可以创建带有说明的标签，用-a指定标签名，-m指定说明文字： 
$ git tag -a v0.1 -m "version 0.1 released" 3628164  // 为commit id为3628164...的commit打上v0.1 的标签注视内容是version 0.1 released 

$ git tag v0.1 //可以查看标签的信息包括文字说明 
还可以通过-s用私钥签名一个标签： 
$ git tag -s v0.2 -m "signed version 0.2 released" fec145a 
```

### 场景:

```shell
初始化版本库，并提交到远程服务器端
mkdir WebApp
cd WebApp
git init 本地初始化
touch README
git add README 添加文件
git commit -m 'first commit'
git remote add origin git@github.com:daixu/WebApp.git
```



每次提交，Git都把它们串成一条时间线，这条时间线就是一个分支 
在Git里，默认有一个主分支，即master分支 
HEAD严格来说不是指向提交，而是指向master，master才是指向提交的，所以，HEAD指向的就是当前分支 
master分支是一条线，Git用master指向最新的提交，再用HEAD指向master 
每次提交，master分支都会向前移动一步，这样，随着你不断提交，master分支的线也越来越长 
Git新建了一个指针叫dev，指向master相同的提交，再把HEAD指向dev，就表示当前分支在dev上 