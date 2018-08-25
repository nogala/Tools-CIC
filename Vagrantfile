# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.box = "nogala/gcloud" 
  config.vm.box_version = "1"
  config.vm.network "forwarded_port", guest: 80, host: 8081, auto_correct: true
  config.vm.network "forwarded_port", guest: 8080, host: 8080, auto_correct: true
  config.vm.provider "virtualbox" do |vb|
     vb.name = "P429CICJL2-Des-premise"
     vb.memory = "4096"
     vb.cpus = "2"
   end
  config.vm.hostname = "P429CICJL2-Des-premise"
end

