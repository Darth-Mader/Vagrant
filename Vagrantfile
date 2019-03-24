vagrant.configure("2") do |config|
	config.vm.define "veni" do |veni|
		veni.vm.box="debian/jessie64"
		veni.vm.network "private_network", ip: "10.0.0.50/24"
		veni.vm.hostname = "debdeb"
	end
	config.vm.define "vidi" do |vidi|
		vidi.vm.box="centos/7"
		vidi.vm.network "private_network", ip: "10.0.0.100/24"
		vidi.vm.hostname = "centforadollar"
	end
	config.vm.define "vici" do |vici|
		vici.vm.box="generic/arch"
		vici.vm.network "private_network", ip: "10.0.0.138/24"
		vici.vm.hostname = "archibald"
	end	
end	
