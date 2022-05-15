# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

if Vagrant.has_plugin? "vagrant-vbguest"
	config.vbguest.no_install = true
	config.vbguest.auto_update = false
	config.vbguest.no_remote = true
end


config.vm.define :vm1 do |vm1|
	vm1.vm.box = "centos/stream8"
	vm1.vm.network :private_network, ip: "192.168.50.5"
	vm1.vm.hostname = "vm1"
end

config.vm.define :vm2 do |vm2|
	vm2.vm.box = "centos/stream8"
	vm2.vm.network :private_network, ip: "192.168.50.6"
	vm2.vm.hostname = "vm2"
end


config.vm.define :vm3 do |vm3|
        vm3.vm.box = "centos/stream8"
        vm3.vm.network :private_network, ip: "192.168.50.7"
        vm3.vm.hostname = "vm3"
end

config.vm.define :vm4 do |vm4|
        vm4.vm.box = "centos/stream8"
        vm4.vm.network :private_network, ip: "192.168.50.8"
        vm4.vm.hostname = "vm4"
end

end
