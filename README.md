# Ansible Collection - my_own_namespace.yandex_cloud_elk

Коллекция содержит роль для размещения файла по указанному пути с заданным содержимым.

#### Installation
`ansible-galaxy collection install my_own_namespace-yandex_cloud_elk-1.0.0.tar.gz`

#### Usage

```yaml
---
- name: Test module
  hosts: localhost
  collections:
    - my_own_namespace.yandex_cloud_elk

  roles:
    - my_own_role
```