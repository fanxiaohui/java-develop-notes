[TOC]

## git
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
- 切换远程分支，并在本地创建该分支：

    ```
    git checkout -b dev_retail origin/dev_retail
    ```

## iTerm 常用快捷键

- 标签
    - 新建标签：command + t
    - 关闭标签：command + w
    - 切换标签：command + 数字 或者 command + 左右方向键
    - 切换全屏：command + enter
- 分屏
    - 垂直分屏：command + d
    - 水平分屏：command + shift + d
    - command + option + 方向键 或 command + [ 或 command + ]
- 其他
    - 清除当前行：ctrl + u
    - 到行首：ctrl + a
    - 到行尾：ctrl + e
    - 清屏：command + r


