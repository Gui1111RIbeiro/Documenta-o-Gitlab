# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    config.vm.box = "centos/7"					#Nome da box que utilizou, ou seja, o <box_name>
    config.vm.box_check_update = false				#Para não atualizar a versão da box
    config.vm.hostname = "srvgitlab"				#Hostname utilizado pro gitlab
    config.vm.network "private_network", ip: "192.168.56.101" 	#Usei este mas pode ser qualquer outro válido

    config.vm.provider "virtualbox" do |vb|
        vb.gui = false						#Desabilitar a interface gráfica GUI para a VM
        vb.name = "gitlab"					#Mudar o nome da VM
        vb.memory = "4096"					#Definir a memória usada da VM
        vb.cpus = "2"						#Definir quantidade de cores que serão usados
    end
end
