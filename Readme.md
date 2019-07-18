# kubernetes auto installer
- k8s version 1.14.3
- install kubelet and kubectl and kubeadm

## how to
1. make inventory file

```
$ touch inventory
$ vim inventory

----

[server]
172.24.17.10 ansible_ssh_pass=password
172.24.17.20 ansible_ssh_pass=password
172.24.17.30 ansible_ssh_pass=password
```

2. start script

```
$ ./ansible-playbook.sh
```