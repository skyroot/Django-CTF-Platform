# Django-CTF-Platform
一个用Django编写的ctf平台

目前用于学习django用，后期能否实际使用，暂看造化



# 功能结构设置

暂定设置，后期依情况改动

##  管理员

暂用django自带的admin模块

##  比赛选手

- 用户名
- 头像

##  赛事

- 赛事名
- 赛事描述
- 开赛时间
- 结束时间
- 赛题

## 比赛得分

- 比赛选手（外键）

- 赛题（外键）

- 解题时间

- 题目分值

  

## 赛题

- 赛事（外键）
- 题目类型
- 题目地址
- 题目名称
- 题目描述
- 解题人数
- 题目分值
- flag

## 邀请码

- 邀请码号
- 是否被使用