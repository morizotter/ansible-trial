# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "chef/centos-7.0"
  config.vm.network "private_network", ip: "192.168.33.20"

  config.vm.provision "ansible" do |ansible|
    ansible.limit = 'all'
    ansible.inventory_path = "hosts"
    ansible.playbook = "site.yml"
    ansible.sudo = true
  end
end
