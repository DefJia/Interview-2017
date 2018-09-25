# Interview-2017
[TOC]
## 功能介绍

- 状态码
  - 0 未到场
    - 签到（权限：候场教室，管理员）
  - 1 已签到
    - 安排（权限：各面试教室，管理员）
  - 2 准备出发
    - 开始面试（权限：候场教室，管理员）
  - 3 面试中
    - 收到任何一条评论（权限：各面试教室，管理员）
  - 4 面试结束

## 文件结构

- register

  - register.php & regcheck.php

    注册界面，仅管理员可用

  - login.php & logincheck.php

    登录

- index.php

- info.exe

  个人信息

- exe.php

  所有按钮的执行

- auto_refreshing.php -> [waiting.php]

  候场教室大屏

## 数据库结构

- 

## 待修复

- 表单验证
  - 非法字符
  - ~~评论页面表单填写的完整性~~
- 主页通过判断用户类型显示不同的按钮
- 未登录直接跳转

------

P.S. 这学年一定要出新版面试系统，代码丑陋到看不下去啦！(Defjia's Flag on 24th Sept, 2018)