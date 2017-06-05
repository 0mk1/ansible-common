# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/xenial64"

  config.vm.box_check_update = false

  config.vm.network "private_network", ip: "192.168.150.150"

  config.vm.provider "virtualbox" do |vb|
   vb.memory = "300"
  end

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "testing.yml"
    ansible.inventory_path = "testing"
  end
end
