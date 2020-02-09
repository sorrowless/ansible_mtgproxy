sbog/mtgproxy
=============

Role to install MTG proxy.

#### Requirements

Ansible 2.4+

#### Role Variables

You can see all vars in `default/main.yml` vars file.

#### Dependencies

None

#### Example Playbook

```yaml
- name: Set the confidence between hosts
  hosts: mtgproxies
  remote_user: root

  roles:
    - mtgproxy
```

#### License

Apache 2.0

#### Author Information

Stan Bogatkin (https://sbog.ru)
