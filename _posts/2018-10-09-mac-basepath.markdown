---
layout: post
title: mac环境变量配置
date: 2018-10-9 12:00:00
description: mac环境变量配置
img: mac.jpg
fig-caption: mac环境变量配置
tags: [MAC]
---
# MAC 环境变量配置
拿今天安装nvm为例  安装后nvm指令在终端提示不是环境变量

* 先到~目录下      '~ ' ==  'User/username/'
* 然后ls命令查看是否有.bash_profile文件
* 如果没有使用后面的命令新建打开 touch ~/.bash_profile  或者 open -t ~/.bash_profile 或者 subl ~/.bash_profile 新建文件
* 使用vi .bash_profile 更改
* PATH 可随便命名 使用export来执行 :为分隔符 修改后保存文件
* 在终端使用source ~/.bash_profile来让配置生效
（如果在Mac系统终端使用export写入环境变量配置只是临时的不能长期保存，电脑开机关机后或者重新打开终端或者另一个窗口仍然会回到没有配置环境变量的状态）

![.base_profile's  code]({{site.baseurl}}/assets/img/2018.10.9/2018.10.9.png)