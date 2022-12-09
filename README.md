# Provisioning role for Fedora Workstation

* first, clone this repository and `cd` into it

* install Ansible and required collections:
`sudo dnf install -y ansible-core && ansible-galaxy collection install -r ansible_collection_requirements.yml`

* then, run Ansible provisioning as follows:
`ansible-playbook playbook.yml -e "workstation_fella=majky" --ask-become-pass`
