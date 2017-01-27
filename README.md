# 注意事项


## 首先修改本地/etc/ansible/ansible.cfg文件

`取消ask_sudo_pass前的注释`

## 在/etc/ansible/hosts添加需要部署的ip

```
[group]
127.0.0.1 ansible_ssh_user=ubuntu ansible_ssh_pass=123456

## ansible执行的命令

`ansible-playbook system-install.yml`

