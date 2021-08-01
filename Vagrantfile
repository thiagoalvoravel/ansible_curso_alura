Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/bionic64"

  config.vm.define "wordpress" do |m|
	   m.vm.network "private_network", ip: "172.17.177.40"
  end

  config.vm.define "mysql" do |m|
    m.vm.network "private_network", ip: "172.17.177.42"
 end

  config.vm.provider "virtualbox" do |v|
	   v.memory = 1024
  end
end
