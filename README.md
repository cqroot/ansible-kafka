# Kafka Ansible

## Installation

Modify the configuration of zookeeper in `roles/kafka/vars/main.yml`.

```bash
ansible-playbook -i hosts site.yml
```

```bash
ansible-playbook -i hosts site.yml --extra-vars "uninstall=true"
```
