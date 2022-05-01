# magma-agw-galaxy

Install Magma Access gateway:
```bash
ansible-playbook deploy-agw.yml
```

SSH and check the AGW install script logs:
```bash
sudo journalctl -fu agw_installation
```
