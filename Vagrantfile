Vagrant.configure("2") do |config|
    config.vm.box = "hashicorp/bionic64"
    
    config.vm.network "private_network", ip: "192.168.56.10"

    config.disksize.size = '20GB'

 config.vm.provider "virtualbox" do |v|
    v.memory = 2048
    v.cpus = 1
 end

end
