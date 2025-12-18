# Ansible Role · install_gcp_cli

Installs Google Cloud CLI (gcloud) on Linux hosts.

## Installation

```bash
ansible-galaxy role install bestiancode.install_gcp_cli
```

Or from GitHub:

```bash
ansible-galaxy role install git+https://github.com/BestianCode/ansible.role.install_gcp_cli.git
```

`requirements.yml`:

```yaml
roles:
  - name: bestiancode.install_gcp_cli
    version: latest
```

## Usage

```yaml
- hosts: all
  become: true
  roles:
    - bestiancode.install_gcp_cli
```

## Links

- **GitHub**: [https://github.com/BestianCode/ansible.role.install_gcp_cli](https://github.com/BestianCode/ansible.role.install_gcp_cli)
- **Galaxy**: [https://galaxy.ansible.com/ui/standalone/roles/BestianCode/install_gcp_cli](https://galaxy.ansible.com/ui/standalone/roles/BestianCode/install_gcp_cli)
