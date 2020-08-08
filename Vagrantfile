
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"

  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
  end

  config.vm.define "wordpress" do |w|
 
    w.vm.network "private_network", ip: "192.168.50.4"

  end
    
  config.vm.define "mysql" do |m|
 
    m.vm.network "private_network", ip: "192.168.50.5"

  end

end