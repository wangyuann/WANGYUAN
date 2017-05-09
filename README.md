# 第一章  
### 1.github是什么    
github是一个分布式的版本控制系统  
### 2.git是什么  
    git是一个开源的分布式版本控制系统，用以有效高速的处理从很小到非常大的项目版本管理  
### 3.学习github的5个理由  
      所有的项目都是开放的，可以了解相关兴趣的项目  
      托管项目 托管代码  
      IT水平和技术快速提升  
### 4.github的优势是什么  
     只支持GIT格式  
     对git完整库完整性协议支持  
     在线文件编辑  
     社交网络元素  
     特色工作模式  
     私有仓库托管  
### 6.github上有可以个人账号 还可以有（ ）账号
     组织
### 7.github上面的两个组成要素是什么
       两个组成要素： 人/组织  仓库/项目
### 8.github上两个重要页面
       数字仪表板 个人界面

### 9.主页菜单都包含什么  
     fallowing 仓库 概览
### 10.仓库的心跳线代表什么   
       仓库内的活跃程度
### 11.star的作用是？
        Star，与watch不同，star相当于收藏，你可以方便地找到你star过的库，但是不会收到关于那个库的任何通知。
### 12.fork的作用是？
       fork的意思是从别人的代码库中复制一份到你自己的代码库，与普通的复制不同，fork包含了原有库中的所有提交记录，fork后这个代码库是完全独立的，属于你自己，你可以在自己的库中做任何修改，当然也可以通过Pull Request向原来的库提交合并请求。
### 13.watch的作用是？
       Watch，意思是关注，关注后，代码库中有新的commit你都会收到通知；
### 14.搜索结果分别有哪些类别 
- 仓库 
- 代码 
- 提交的注释 
- 用户 
- 某个bug 

### 15,你在github上挖到什么宝
- 项目。技术人员  
- 命令行终结   Ctrl+C 强制退出  
- 命令行翻页和退出 git log  
- 新建代码仓库  git init  
- 下载一个项目和它的整个代码历史   
`url  https://githubcom/[userName]/reposName  
git clone [url]` 
- 添加指定文件到暂存区  `git   add[file1][file2] ` 
- 代码提交 `git commit -m[meggest]`  
- 查看信息 `git ststus`  
- 查看历史版本  
`git log  
git log --oneline`  

# 第二章
### 1.个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
- New repository 新建仓库
- Import repository 引入仓库
- New gist 代码片段
- New organization 建新组织

### 2.如何能将仓库中的html文件直接解析成页面？
`settings   
sourse   
master branch`
### 3.如何删除仓库
`settings  
delete this repository`
### 4.Bash是什么操作系统的命令
linux
### 5.Pwd是什么命令
打印当前目录
### 6.Cd是什么命令
改变路径
### 7.Echo是什么命令
输出
### 8.配置git用户名的命令
`git config --global user.name ""`
### 9.配置邮箱的命令
`git config --global user.email ""`
### 10.命令行换行方式
    /
### 11.命令行终结方式
 ctrl+c 强制退出
### 12.使用命令行比GUI方式有何优势
  git命令行拉取提交速度快
### 13.提交到本地仓库时为什么有暂存区
    
### 14.新建代码仓库的命令
1. git init
2. 下载一个项目和它的整个代码历史  
`url <https://githubcom/[userName]/reposName>  
git clone [url]`

### 15.git clone [url] 这个命令的作用是
克隆仓库
### 16.添加指定文件到暂存区的命令
`git add[file1][file2]`
### 17.删除工作区文件，并且将这次删除放入暂存区的命令
`rm  a.txt`
### 18.改名文件，并且将这个改名文件放入暂存区的命令
`git mv[file -original][file - renamed]`
### 19.提交暂存区到仓库的命令
`git commit -m[massage]`
### 20.直接从工作区提交到仓库的命令
    
### 21.显示变更信息的命令
`git status`
### 22.查看历史信息的命令
`git log  
git log --oneline`
### 23.Commit的意义是
提交
### 24.Pull的意义是
远程仓库-->本地
### 25.Push的意义是
推送文件或代码
# 第三章    
### 1.Markdown是什么
MarkDown轻量级编辑语言  
是一个Web上使用的文本到HTML的转换工具；
### 2.Markdown的特点
- 兼容HTML  
- 在线观看  
- 平台支持  
- 排版样式简单

### 3.Markdown的用途
IT人士：写日志，技术文稿，记录代码片段，撰写文档
### 4.编辑工具
- Mac OS :Mou
- Windows :MarkdownPad 、MarkPad
- Linux: ReText
- Web:简书、Github、有道云笔记

### .MarkDown的区块元素和区段元素分别包含哪些  
区块元素：
- 段落和换行
- 标题
- 区块引用
- 列表
- 代码区块
- 分隔线

区段元素：
- 链接
- 强调
- 代码
- 图片
