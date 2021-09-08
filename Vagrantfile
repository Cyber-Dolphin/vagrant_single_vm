Vagrant.configure("2") do |config|

  config.vm.box = "cyberdolphin_ubuntu"

  config.vm.synced_folder "./data", "/vagrant"

  config.vm.network "private_network", ip: "192.168.56.110",

    name: "VirtualBox Host-Only Ethernet Adapter"

  config.vm.provider "virtualbox" do |vb|

     vb.memory = "1024"

     vb.cpus = "1"

  end

  config.vm.boot_timeout = 800
  
  config.ssh.username = "sadmin"

  config.ssh.private_key_path = "../ssh_auto/priv_cyber_openssh"

end
