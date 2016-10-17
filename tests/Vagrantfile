# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "bento/ubuntu-16.04"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
  end
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "./test-vagrant.yml"
  end
  config.vm.provision "ansible_local" do |ansible|
    ansible.playbook = "./test-vagrant.yml"
    ansible.install = true
  end
end
