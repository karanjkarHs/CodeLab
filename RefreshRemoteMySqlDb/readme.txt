ansible-vault encrypt_string 'xxxxx' --name 'user_password'

--vault-password-file /path/vault-password-file secrets.yml

ansible-vault create secrets.yml

ansible-playbook --ask-vault-pass refreshNewStage.yml -i /inventory.txt

