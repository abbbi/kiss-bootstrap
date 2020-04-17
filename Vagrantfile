# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.boot_timeout = 1800
  config.vm.synced_folder ".", "/vagrant", disabled: true
  config.vm.box_check_update = true
  config.vm.boot_timeout = 1800
  config.vm.boot_timeout = 1800
  config.ssh.shell = 'ash'
  config.vm.guest = "debian"
  config.vm.provider :libvirt do |v, override|
    v.disk_bus = "sata"
    v.nic_model_type="e1000"
    v.driver = "kvm"
    v.video_vram = 256
    v.memory = 2048
    v.cpus = 2
  end
end
