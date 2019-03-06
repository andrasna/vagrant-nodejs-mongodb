Vagrant.configure("2") do |config|
  config.vm.box = "generic/ubuntu1804"
  config.vm.provision "shell", path: "script.sh"
  config.vm.synced_folder "src/", "/srv/website"
end