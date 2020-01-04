[toc]
# git从零到一
## git安装
1. ubuntu安装

`apt-get install git`
## git安装版本
`git --version`

## 初次使用
### 用户身份录入
`git config --global user.name "Your Name"`

`git config --global user.email you@example.com`

作用:识别使用者身份，可以使用注册github的账号与邮箱

## git命令详解
### 查看帮助文档

`git help`:

列出所有git命令的解释:**`git help`+命令名称

### 检查远程仓库配置

`git remote -v`

### 文件操作
#### 创建本地文件夹
`mkdir tongxipython`

#### 本地文件夹初始化
`git　init`

初始化git,生成.git文件夹，专门用来存放一些git需要的数据和资源，用于管理当前目录下的文件
#### 查看本地文件的状态
`git statues`

查看git仓库中的状态
git中文件的三种状态:

**git一般将文件划分为三种状态:**
1. 暂存
2. 修改
3. 提交
![image](https://note.youdao.com/yws/api/personal/file/WEBf94bef16ba60450534f8838a406ca8c4?method=download&shareKey=0faadddbb72b797d0c95f58398b8908f)
- 工作区:存放新增和修改的文件
- 暂存区:存放下次需要提交的文件清单(在.git目录中)
- git仓库:存放已提交的文件

#### git add
**将工作区中的新修改的文件标记一下追踪，然后生成快照，记录起来，放到暂存区中**
`git add .`:添加当前文件夹下的所有文件

`git add **.cpp`:添加当前文件夹下的cpp类型文件
#### git commit
**将暂存区里的记录的文件，存储到git仓库里面，只有这样，我们才能将项目push到远程服务器上**



