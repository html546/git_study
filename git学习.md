git的学习
========
- git全局配置

    - git config --global user.name "html546"
    - git config --global user.email "1776787598@qq.com"
- 查看git配置
    - git config --list / git config --l
- git init / git init 仓库名
    - 初始化git仓库
- 列出所有子目录
    - Unix：ls -la windows: dir/a
- ctrl + l 清屏
- git clone https://github.com/biaoyansu/15.x.git
    - 从github上下载
- git status
    - 查看仓库状态
- git add .
    - 将所有修改添加至暂存区
- git commit -m "描述"
    - 提交版本
- git log 
    - 查看版本记录
- git checkbout xxx
    - 穿越到指定的历史节点
* 三个阶段
    1. modified : 已修改
    2. staged : 已暂存
    3. committed : 已暂存
- git log -p
    - 查看最近的版本修改了什么
- git log --oneline
    - 一行显示版本历史
- git log --oneline --all
    - 一行显示所有版本历史
- git tag -a 标签名 -m "备注"
    - -a---annotated 有注释的
    - 给版本加标签
- git tag 
    - 列出所有标签
- git show 标签名
    - 查看某个标签的详细信息
- git checkout 标签名
    - 回溯至标签所在的提交
- git branch 分支名
    - 创建分支
- git checkout 分支名
    - 切换分支
- git log --all --graph
    - 图示全部历史记录
- git checkout -b 分支名
    - 创建并切换至分支
- git merge 分支名
    - 合并分支
- git remote add 远程名称 远程地址
    - 添加远程地址
- git remote 
    - 列出所有远程仓库
- git remote
    - 列出所有远程仓库详细信息
- git push -u 远程名 分支名
    - 上传代码
- git clone 仓库地址
    - 克隆(拷贝)仓库
- git pull
    - 获取远程更新