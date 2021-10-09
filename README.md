Ansible Role: Terraform
=========

![Terraform](https://img.shields.io/badge/-Terraform-623CE4?style=for-the-badge&logo=Terraform&logoColor=white)
![Ubuntu](https://img.shields.io/badge/-Ubuntu-E95420?style=for-the-badge&logo=Ubuntu&logoColor=white)

Install [Hashicorp's Terraform](https://www.terraform.io/) latest version on Ubuntu.

---

Requirements
------------

- **[jq](https://github.com/stedolan/jq)** must be installed but the role takes care of this at the beginning

Example Playbook
----------------

```bash
ansible-galaxy install git+https://github.com/theJaxon/ansible-role-terraform
```

```yml
- hosts: all
  roles:
  - ansible-role-terraform
```

License
-------

GPL

Author Information
------------------

Created by [theJaxon](https://github.com/theJaxon)
