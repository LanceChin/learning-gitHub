# 如何使用gitHub

### 克隆仓库篇
- 首先先创建一个远程仓库
- 然后在一个空的文件夹里打开GitBush，
输入git clone https://github.com/LanceChin/studyGit.git（前面的连接指的是你仓库的地址）
- 等待
- 之后会显示一个文件夹，名字就是你远程仓库的名字里面有一个隐藏的git，以及文件
这样的仓库就算克隆好了。

- 之后就可以在这个基础上去进行使用了

### 上传文件篇

- 创建一个分支

- 切换到新创建的分支上

- 然后直接在文件上进行修改即可，此时所改的东西是在分支上改的，而主分支上的东西并没有改变

- 修改之后可以git 

- status一下看看它的状态如何

- 然后提交到暂存区  git add *

- 之后提交到版本库

- 这时主分支上的内容依旧没有改变

- 然后切换到主分支上可以查看一眼主分支上的内容

- 然后进行分支合并 git merge dev-test
然后可以git log一下看看信息
- 这时主分支上的内容也就发生了改变
- 然后把修改好的东西提交到远程仓库，输入指令
git push  https://github.com/LanceChin/studyGit.git  master（要提交的分支名称）
这样就提交到远程仓库了

### 协同开发篇

- 如果说有人要协同开发，现在gitHub上创建一个新分支 feature-index
 
- 然后新建一个文件夹
git clone https://github.com/LanceChin/studyGit.git 不需要加分支名称

- 然后进入这个文件夹里
在这里gitbash 一下

- 默认克隆的是主分支

- 在主分支上创建一个分支，分支名称与github上新分支的名称相同feature-index

- 然后切换到feature-index上

- 输入pull https://github.com/LanceChin/studyGit.git
feature-index（gitHub上新分支名称）

- 这样就可以了。

### 搭建博客篇

- 首先新建一个仓库 仓库的名字前缀要和用户名一样

- 例如我的名字是LanceChin 

- 我的仓库名字就叫LanceChin.github.io

- Add a license : GNU General Public License v3.0

- 然后点击settings

- 中间部位就有一个GitHub Page  

- 第一行就会有这个提示' Your site is published at https://lancechin.github.io/'

- 然后点击那个网站就是你的博客了

- 你可以选择样式为它

- 还可以自己编辑代码去实现样式，至少目前我是这么理解的，没有测试，以后会测试一下

- 至于这个域名low的问题，过几天解决。






