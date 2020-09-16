cloud3rsio.zabbix50_agent
=========

Install zabbix-agent.

Installation
------------

```bash
$ ansible-galaxy install cloud3rsio.zabbix50_agent
```

Requirements
------------

Nothing.

Role Variables
--------------

| Key | Default Value | Type |
| ------------- | ------------- | ------------- |
| `zabbix50_agent_packages` | Reference to [defaults/main.yml](defaults/main.yml) | Array |

Dependencies
------------

- `cloud3rsio.yumrepo_zabbix50`

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: cloud3rsio.zabbix50_agent
```

License
-------

[MIT](LICENSE)

Author Information
------------------

- youyo
