Simple Setup Project
====================

e.g. https://opensource.com/article/18/3/manage-workstation-ansible

## Prerequisites

1. Install Ansible (Ubuntu & Co.)


    sudo apt-get install software-properties-common
    sudo apt-add-repository ppa:ansible/ansible
    sudo apt-get update
    sudo apt-get install ansible

Other platforms: see [Installation Guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## Usage

### Remote Repository

    sudo ansible-pull -U https://github.com/<user_name>/simple-setup.git

## More

Expand this, e.g. by using [Roles](https://docs.ansible.com/ansible/latest/user_guide/playbooks_reuse_roles.html)

This approach can be automated with a little tweaking. See [this article](https://opensource.com/article/18/3/manage-your-workstation-configuration-ansible-part-2) on how to do that.

* https://gitlab.com/jsherman82/ansible_article
