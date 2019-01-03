# Playbook update Repos

#### Features

  - Update Ambari repo
  - update HDP repo
  - Update HDP UTILS repo
  - Update NIFI repo

#### Requirements
To use this role you should add the repo url  in /roles/nameroles/vars/main.yml  example update repo Ambari:
```sh
ambari_repo: http://host.com/ambari/centos7/2.x/updates/2.6.2.0
```
### Inventory
```sh
[hosts]
host1
host2
host3
```

### Example deployement
```sh
ansible-playbook main.yml -i listhosts
```





Author
----

Mohamed Melki
