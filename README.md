# Ansible Playbooks

## Prerequisites
-   Install [ansible](https://docs.ansible.com/ansible/latest/index.html) on Mac via brew
```bash
brew install ansible
```

-   Or on Ubuntu via APT under root user
```bash
apt update
apt install -y software-properties-common
add-apt-repository --yes --update ppa:ansible/ansible
apt install -y ansible
```

## WireGuard VPN server configuration

## Using

All commands will be executed on instance at any hosting, this param configured at `ansible/inventory.yaml`.

```bash
ansible-playbook --ask-vault-pass wireguard.yaml -v
```
