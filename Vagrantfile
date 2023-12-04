# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    config.vm.define :servidorweb do |servidorweb|
      servidorweb.vm.box = "debian/bullseye64"
      servidorweb.vm.hostname = "servidorweb"
      servidorweb.vm.synced_folder ".", "/vagrant", disabled: true
    end
    
  end
  