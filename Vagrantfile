Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.provision "shell", path: "script.sh"
  config.vm.synced_folder "src/", "/srv/website"
end