# Guia de início rápido

### O QUE É
Sistema de infraestrutura como serviço para configuração do MySql e do Wordpress apresentado na formação DevOps da Alura.

### OBJETIVO
Dispor de um sistema para o gerenciamento da infraestrutura de um servidor Ubuntu com os serviços de BD e CMS.

### INSTALAÇÃO LOCAL
* virtualbox 6.1 
* vagrant 2.2.14
* ansible 2.9.17

```shell
sudo apt install virtualbox && \
sudo apt install vagrant && \
sudo apt install ansible
```

### EXECUÇÃO
* Para executar o projeto faça:
1. Suba os boxes definidos no Vagrantfile
```shell
vagrant up
```
2. Execute as configurações do provisioning.yml
```shell
ansible-playbook -i hosts provisioning.yml
```

### TESTE MANUAL
* Para testar acesse:
    * http://172.17.177.40/

* Para configurar o Wordpress, acesse:
    * http://172.17.177.40/wp-admin/install.php
----------------------------
#### SE VOCÊ CHEGOU ATÉ AQUI
Muito obrigado pela atenção!

#### SOBRE O AUTOR/ORGANIZADOR
Danilo Costa.
