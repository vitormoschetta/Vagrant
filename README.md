# Vagrant

Vagrant é um gerenciador de Máquinas Virtuais. Ele trabalha com diversos provedores de Maquinas Virtuais, entre eles o Virtual Box.

<br>


### Install VirtualBox:

<https://www.virtualbox.org/wiki/Linux_Downloads>

<br>


### Install Vagrant:

<https://www.vagrantup.com/downloads>


Get Started Vagrant:

<https://learn.hashicorp.com/tutorials/vagrant/getting-started-index>


### Comandos Vagrant:


Verificar se o vagrant está up:
```
vagrant status
```

Verificar configurações do Vagrant
```
vagrant ssh-config
```

Criar um arquivo com nome 'Vagranfile'. 
Exemplo de conteúdo no Vagrantfile (iniciar uma Maquina Virtual Ubuntu 18.04 LTS 64-bit):
```
Vagrant.configure("2") do |config| 
    config.vm.box = "hashicorp/bionic64"
end
```

Conectar a maquina virtual do Vagrant:
```
ssh -p 2222 vagrant@127.0.0.1
Senha: vagrant
```

Stop Vagrant:
```
vagrant halt
```


<br>

### Outros

Instalar Docker no Ubuntu via terminal:

<https://www.hostinger.com.br/tutoriais/install-docker-ubuntu>

Instalar o Docker Compose:

<https://www.digitalocean.com/community/tutorials/how-to-install-docker-compose-on-ubuntu-18-04-pt>


Instalar Git:

<https://www.digitalocean.com/community/tutorials/como-instalar-o-git-no-ubuntu-18-04-inicio-rapido-pt>


Instalar Dotnet SDK no Ubuntu:

<https://docs.microsoft.com/pt-br/dotnet/core/install/linux-ubuntu#1804->