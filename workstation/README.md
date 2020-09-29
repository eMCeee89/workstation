Provisioning role for Fedora 32

Install ansible first, then run locally as follows:
  ansible-playbook playbook.yml -e "workstation_fella=majky" --ask-become-pass
