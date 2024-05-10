
Vagrant.configure("2") do |config|

  config.vm.define "linux1" do |linux1|
    linux1.vm.box = "ubuntu/focal64"
    linux1.vm.network "public_network" 
    linux1.vm.provider "virtualbox" do |vb|
      vb.name = "linux1"
      vb.memory = "4096"
      vb.cpus = "4"
    end
  end

  config.vm.define "linux2" do |linux2|
    linux2.vm.box = "ubuntu/focal64"
    linux2.vm.network "public_network" 
    linux2.vm.provider "virtualbox" do |vb|
      vb.name = "linux2"
      vb.memory = "4096"
      vb.cpus = "4"
    end
  end

  config.vm.define "linux3" do |linux3|
    linux3.vm.box = "ubuntu/focal64"
    linux3.vm.network "public_network" 
    linux3.vm.provider "virtualbox" do |vb|
      vb.name = "linux3"
      vb.memory = "4096"
      vb.cpus = "4"
    end
  end

  config.vm.define "linux4" do |linux4|
    linux4.vm.box = "ubuntu/focal64"   
    linux4.vm.network "public_network" 
    linux4.vm.provider "virtualbox" do |vb|
      vb.name = "linux4"
      vb.memory = "4096"
      vb.cpus = "4"
    end
  end
    
  config.vm.provision "shell", inline: <<-SHELL
    apt update
    apt install -y nginx
  SHELL
end

