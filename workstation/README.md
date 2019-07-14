Provisioning role for Fedora 30

Install first:
  - ansible
  - python3-dnf

Run locally as follows:
  ansible-playbook playbook.yml -e "workstation_fella=niki" --ask-become-pass
