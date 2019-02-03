# Fedora provisioner

## Requirements

```bash
sudo dnf install -y ansible libselinux-python
```

## Provisioning

```bash
ansible-playbook -c local -i 'localhost,' playbook.yml --ask-sudo-pass
```
