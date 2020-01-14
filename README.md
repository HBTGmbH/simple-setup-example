Simple Setup Project
====================

## Prerequisites

1. Install Ansible (Ubuntu & Co.)
```bash
sudo apt install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
```

Other platforms: see [Installation Guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## Usage

### Remote Repository
```bash
sudo ansible-pull -U https://github.com/<user_name>/simple-setup-example.git
```

## More

Expand this, e.g. by using [Roles](https://docs.ansible.com/ansible/latest/user_guide/playbooks_reuse_roles.html)

This approach can be automated with a little tweaking. See [this article](https://opensource.com/article/18/3/manage-your-workstation-configuration-ansible-part-2) on how to do that.
