# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.provider "virtualbox" do |v|
    v.memory = 2048
    v.cpus = 2
  end

  config.vm.define "el6" do |x|
  	x.vm.box = "bento/centos-6.7"
  end

  config.vm.define "el7" do |x|
  	x.vm.box = "bento/centos-7.2"
  end
end
