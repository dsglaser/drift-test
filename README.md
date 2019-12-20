# drift-test
This basic playbook is to show different ways to approach a check script from an ansible host to a managed system. The playbook will run and report 'changed' for anything that would have been changed if the playbook was run in normal mode. The playbook should be run as such:

ansible-playbook -i inventory drift-test.yml
