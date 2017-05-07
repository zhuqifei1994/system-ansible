# 注意事项

## 在/etc/ansible/hosts添加需要部署的ip

```
[group]
Your_ip_address ansible_ssh_user=Your_ssh_user ansible_ssh_pass=Your_ssh_password
```
## 使用roles脚本的话需要修改创建用户的信息
修改 **group_vars/all** 文件当中 user 和 password 信息

## ansible 普通方法执行的命令

`ansible-playbook system-install.yml`

## ansible roles 方法执行的命令
`ansible-playbook roles-install,yml`