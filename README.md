# ansible-redmine

Install Redmine on CentOS.

```console
$ yum install -y epel-release
$ yum install -y ansible git
```

```console
$ git clone https://github.com/onozaty/ansible-redmine.git
$ cd ansible-redmine
$ ansible-playbook -i hosts playbook.yml
```
