

ansible-playbook ansible/playbooks/setup_new_server.yml -i ansible/inventory/hosts.ini --check --diff



ansible-playbook ansible/playbooks/monitoring-node-playbook.yml -i ansible/inventory/hosts.ini --check --diff



ansible-playbook ansible/playbooks/monitored-servers-playbook.yml -i ansible/inventory/hosts.ini --check --diff

---
