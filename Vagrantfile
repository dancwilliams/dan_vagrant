Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.provision :shell, path: "bootstrap.sh"
  config.vm.network :forwarded_port, guest: 1313, host: 1313
  config.vm.synced_folder "C:/\Users/\dancw/\Documents/\git", "/home/vagrant/git"
end
