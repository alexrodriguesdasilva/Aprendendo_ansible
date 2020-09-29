Alteração do arquivo hosts

Agora atribuimos o usuario e a chave do server no arquivo hosts, Com isso não precisamos mais passar o usuario e caminho da chave do comando ansible

Novo comando para aplicar alterações:
$ sudo ansible-playbook provisioning.yml -i hosts