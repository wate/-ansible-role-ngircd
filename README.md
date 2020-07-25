ngircd
=========

ngIRCのインストールとセットアップを行います

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

### ngircd_global_cfg

ngIRCの全般設定を指定します

```yml
ngircd_global_cfg:
  name: c.example.net
  info: Server Info Text
  listen: 127.0.0.1
```


Example Playbook
----------------

```yml
- hosts: servers
  roles:
     - role: ngircd
```

License
-------

MIT
