

#### Ansible 実行

```
$ cd path/to/ansible-template/ansible
$ ansible-playbook -v playbooks/site.yml -i inventories/localhost
```

#### SSH経由で実行したい場合
 
```
$ ssh-keygen -t rsa
ノンパスでEnter
$ cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys
$ chmod 600 ~/.ssh/authroized_keys
```
