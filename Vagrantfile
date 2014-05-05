# encoding: utf-8

Vagrant.configure("2") do |config|
  config.vm.define "master" do |machine|
    machine.vm.box = "apollo-master"
  	config.vm.box_url = "http://files.vagrantup.com/precise64.box"
  	config.vm.hostname = "apollo-master"
  	config.vm.provision :shell, :path => "scripts/bootstrap.sh"
  end
end