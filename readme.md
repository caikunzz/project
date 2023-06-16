# git是什么
集中式版本控制系统（CVS）=> svn
分布式版本控制系统（DVCS） => git

# git的作用
在项目开发的进程中 对值得记录的时间节点进行"备份"，方便后期恢复
方便团队协作开发


# git管理文件的三种状态
- 已修改（modified）：表示修改(新增、更新、删除)了文件，但还没保存到数据库中。 （红色）
- 已暂存（staged） ：表示对一个已修改文件的当前版本做了标记，使之包含在下次提交的快照中
- 已提交（committed）：表示数据已经安全地保存在本地数据库中
这会让我们的Git项目拥有三个阶段：工作区、暂存区以及Git目录


# 初次运行Git前的配置
配置用户名和邮箱
....bash
git config --global user.name "shangzhaozhao"
git config --global user.email "3064159737@qq.com"


查看配置信息
git config --list
git config user.name
git config user.email


# 获取git仓库（repo）
- 自行初始化git仓库（git init）
- 克隆远程（服务器）仓库 （git clone  【repo_url/仓库地址】）
    git clone http://192.168.122.33:3080/shenhongchun/SLXM.git


U（Untracked） 表示未跟踪（新增）
A（added）     表示
M（modified）  表示跟踪后被修改