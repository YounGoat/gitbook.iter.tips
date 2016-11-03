#	Ansible

##	怎样支持使用密码登录远端服务器？

在远端服务器上配置证书公钥，是经典的授权方式。但某些场景下需要直接使用密码：

```bash
# Registered from hosts inventory.
[all:vars]
ansible_ssh_user=root
ansible_ssh_pass=password
ansible_ssh_port=22
```

可能会遇到这样的报错：
```bash
ansible all -m ping
# OUTPUT:
# 10.0.0.100 | FAILED! => {
#    "failed": true,
#    "msg": "to use the 'ssh' connection type with passwords, you must install the sshpass program"
# }
```

安装 sshpass 软件可以解决这个问题：
```bash
# 通过 YUM 安装
yum install sshpass

# 检查安装结果
sshpass -V
# sshpass 1.05 (C) 2006-2011 Lingnu Open Source Consulting Ltd.
# This program is free software, and can be distributed under the terms of the GPL
# See the COPYING file for more information.
```
