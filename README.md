# drift-test
This basic playbook is to show different ways to approach a check script from an ansible host to a managed system. The playbook will run and report 'changed' for anything that would have been changed if the playbook was run in normal mode. The playbook should be run as such:

ansible-playbook -i inventory drift-test.yml --check

Supplying the --diff flag can also be beneficial as modules that support it will show what they would have done, such as what parts of a file would hve been changed. This isn't beneficial for 'shell' modules however.



