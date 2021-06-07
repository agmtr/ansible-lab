$box = "centos/7"

Vagrant.configure("2") do |config|
  config.vm.define "web" do |web|
    web.vm.box = $box
    web.vm.network "private_network", ip: "192.168.50.10"
  end
  config.vm.define "db" do |db|
    db.vm.box = $box
    db.vm.network "private_network", ip: "192.168.50.11"
  end
end

