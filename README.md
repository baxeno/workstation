# Fedora Workstation setup with Ansible

This bootstraps a Fedora Workstation with some extra development goodies using Ansible (Python3 edition).

```bash
$ sudo dnf install -y ansible-python3
$ ansible-playbook -K post_install.yml
```

**TODO:**

- Use variables in gitconfig.
