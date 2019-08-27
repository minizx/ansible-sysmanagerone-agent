# sysmanagerone-agent


# examples of using roles
```
- hosts: all
  roles:
    - role: sysmanagerone-agent
      sysmanagerone-agent_mode: install
      sysmanagerone_id: customerid
      sysmanagerone_server_ip: 1.1.1.1
      sysmanagerone_dir: /usr/local/sysmanagerone
```   
