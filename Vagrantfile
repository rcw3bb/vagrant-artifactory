Vagrant.configure("2") do |config|
  config.vm.box = "rcw3bb/ubuntu-artifactory"
  config.vm.box_version = "20190916.0.1"
  config.vm.network "forwarded_port", guest: 8081, host: 8081, id: "artifactory", auto_correct: true
end
