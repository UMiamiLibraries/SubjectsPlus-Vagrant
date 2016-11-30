# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.provision "shell", path: "install_sp.sh"
  config.vm.network "forwarded_port", guest: 80, host: 8889
  config.vm.network "forwarded_port", guest: 3306, host: 7779
end
