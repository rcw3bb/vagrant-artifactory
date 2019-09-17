Vagrant.configure("2") do |config|
  config.vm.box = "rcw3bb/ubuntu-artifactory"
  config.vm.network "forwarded_port", guest: 8081, host: 8081, id: "artifactory", auto_correct: true

  # config.vm.provider "virtualbox" do |vb|
  #   vb.memory = "4096"
  # end

end
