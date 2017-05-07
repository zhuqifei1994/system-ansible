# 注意事项

## 在/etc/ansible/hosts添加需要部署的ip

```
[group]
127.0.0.1 ansible_ssh_user=ubuntu ansible_ssh_pass=123456
```
## 使用roles脚本的话需要修改创建用户的信息
修改 **group_vars/all** 文件当中 user 和 password 信息

## ansible执行的命令

`ansible-playbook system-install.yml`

## ansible roles执行的命令
`ansible-playbook roles-install,yml`