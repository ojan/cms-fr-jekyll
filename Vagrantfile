# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  
  config.vm.box = "ubuntu/trusty64"

  config.vm.hostname = "cmsfr"

  config.vm.network "private_network", ip: "192.168.56.100"

  config.ssh.forward_agent = true

  config.vm.provision "shell", path: "install.sh"

end
