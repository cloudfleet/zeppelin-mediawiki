# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "debian/jessie64"

  config.vm.network "private_network",
                    type: "dhcp"
  
  config.vm.provision "shell",
                      inline: "sudo id"
end
