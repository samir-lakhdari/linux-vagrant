# docker-vagrant
git clone https://github.com/go2mylearn/linux-vagrant.git
cd linux-vagrant

# Pour VMware
cp Vagrantfile.vmware Vagrantfile
vagrant up

# Pour Virtualbox
cp Vagrantfile.virtualbox Vagrantfile
vagrant up

# Pour Hyper-V
cp Vagrantfile.hyperv Vagrantfile
vagrant up



