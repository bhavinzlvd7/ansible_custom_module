# ansible command to test

python -m library.my_temp args/my_temp__test_1.json

ansible-playbook my_temp__test_set_1.yml -e "vm_name=localhost"

ansible-playbook my_temp__test_set_2.yml -e "vm_name=localhost"

ansible-playbook my_temp__test_set_3.yml -e "vm_name=localhost"

