# ansible-jenkins

- Install Jenkins Servers with Ansible.
- OS: CentOS 7

## Before Install
- Use DNS Server or update /etc/hosts for all servers.
- Update hosts file.

### Install Jenkins Server.
- Run the playbook.

```
ansible-playbook -i hosts jenkins.yml
```
