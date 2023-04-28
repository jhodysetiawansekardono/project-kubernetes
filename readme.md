# HowTo
Note: khusus cluster yang isolated dari Internet

1. Sesuaikan file hosts.yaml dan variables.yaml
2. Jalankan:
```
ansible-playbook kubernetes.yaml -u ubuntu --become --become-user=root
```