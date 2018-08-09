# 目录

[TOC]

## iTerm 常用快捷键

- 标签
    - 新建标签：`command + t`
    - 关闭标签：`command + w`
    - 切换标签：`command + 数字` 或者 `command + 左右方向键`
    - 切换全屏：`command + enter`
- 分屏
    - 垂直分屏：`command + d`
    - 水平分屏：`command + shift + d`
    - `command + option + 方向键` 或 `command + [` 或 `command + ]`
- 其他
    - 清除当前行：`ctrl + u`
    - 到行首：`ctrl + a`
    - 到行尾：`ctrl + e`
    - 删除到文本末尾：`ctrl + k`
    - 删除光标之前的单词：`ctrl + w`
    - 清屏：`command + r`

## Git 常用命令

- 切换 git 分支流程：
    - 一般代码 clone 到本地都是 master 分支；
    - 查看远程分支：`$ git branch -a`；
    - 查看本地分支：`$ git branch`；
    - 切换分支：`git checkout -b local_dev_bas origin/lumi_dev_bas`；
        - 上面的指令有两个含义：
            - 先本地创建 `local_dev_bas` 分支；
            - 然后切换到 `local_dev_bas` 分支，该分支拉取的是远程分支 `lumi_dev_bas` 的代码；
- 配置用户名和密码：
    
    ```
    git config --global user.name "wangliyong"
    git config --global user.email "liyong.wang@lumiunited.com"
    ```
- 生成 SSH key：

    ```
    ssh-keygen -t rsa -C "liyong.wang@lumiunited.com"
    ssh-agent -s
    ssh-add ~/.ssh/id_rsa
    clip < ~/.ssh/id_rsa.pub
    ```
