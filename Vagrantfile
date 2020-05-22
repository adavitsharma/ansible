Vagrant.configure("2") do |config|
config.vm.define "node1" do |node1|
  node1.vm.box = "bento/centos-6.7"
  node1.vm.hostname = "inframon.mylab014.com"
  #config.vm.network "private_network"
  node1.vm.network "private_network", ip: "192.168.56.14"

end
config.vm.define "node2" do |node2|
  node2.vm.box = "bento/centos-6.7"
  node2.vm.hostname = "inframon.mylab015.com"
  #config.vm.network "private_network"
  node2.vm.network "private_network", ip: "192.168.56.15"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
    vb.cpus = "2"
end
end
config.vm.define "node3" do |node3|
  node3.vm.box = "bento/centos-6.7"
  node3.vm.hostname = "puppetmaster.mylab.local"
  #config.vm.network "private_network"
  node3.vm.network "private_network", ip: "192.168.56.16"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
    vb.cpus = "2"
end
end
config.vm.define "node4" do |node4|
  node4.vm.box = "bento/centos-6.7"
  node4.vm.hostname = "puppetnode.mylab.local"
  #config.vm.network "private_network"
  node4.vm.network "private_network", ip: "192.168.56.17"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
    vb.cpus = "2"
end
end
end
