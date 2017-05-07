# 注意事项

## 在/etc/ansible/hosts添加需要部署的ip

```
[group]
127.0.0.1 ansible_ssh_user=ubuntu ansible_ssh_pass=123456
```

## ansible执行的命令

`ansible-playbook system-install.yml`

## ansible roles执行的命令
`ansible-playbook roles-install,yml`