# Vagrantfile for almalinux. almalinux is based on RHEL
Vagrant.configure("2") do |config|
  config.vm.box_check_update = false
  config.vm.box = "almalinux/8"
  config.vm.provider "virtualbox"
  config.vm.hostname = "almalinux8"
  config.vm.define "almalinux8"
  config.vm.synced_folder "/Users/xxx/wrk/netauto/", "/netauto"
  config.vm.provision "shell", path: "config.sh"
end