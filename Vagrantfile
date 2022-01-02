#
PROVIDER = "vmware_desktop"
#PROVIDER = "virtualbox"
BOX_BASE = "centos/7"
VM_HOSTNAME = "docker"

Vagrant.configure("2") do |config|
  config.vm.define "docker" do |docker|
    docker.vm.box = BOX_BASE
    docker.vm.hostname = VM_HOSTNAME
    docker.vm.provider PROVIDER do |vm|
      vm.gui = true
    end
    docker.vm.provision "shell", path: "install-docker.sh"
  end
end
