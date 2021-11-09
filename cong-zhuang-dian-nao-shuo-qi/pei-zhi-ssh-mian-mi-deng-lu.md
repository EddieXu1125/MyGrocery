---
description: 想省事儿登录？先配置这个吧
---

# 配置SSH免密登录

## 在客户端



1. 先生成密钥 <mark style="color:blue;">`ssh-keygen -b 4096`</mark>

&#x20;2\. 然后进行密钥的传输：

如果客户端是Mac或者linux系统可以使用ssh-copy-id命令

<mark style="color:blue;">`ssh-copy-id -i ~/.ssh/id_rsa.pub 目标用户名@目标IP`</mark>

如果是Windows系统，可以使用scp命令,注意是反斜杠

<mark style="color:blue;">`scp C:\USer\用户名.ssh\id_rsa.pub 目标用户名@目标IP`</mark>

## 在服务器端
