# -*- mode: ruby -*-
# vi: set ft=ruby ts=2 sw=2 tw=0 et :

ENV['ANSIBLE_ROLES_PATH'] = "../"

Vagrant.configure(2) do |config|
  config.vm.box = "debian/stretch64"
  config.vm.box_check_update = true
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "256"
  end
  config.vm.provision "ansible" do |ansible|
    ansible.sudo = true
	ansible.playbook = "tests/vagrant.yml"
  end
end
