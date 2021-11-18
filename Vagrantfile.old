
Vagrant.configure("2") do |config|
  ENV['VAGRANT_DEFAULT_PROVIDER'] = 'docker'
  config.vm.provider "docker" do |d|
#   d.vagrant_vagrantfile = "../<path>/Vagrantfile"
    d.image = "centos/7" 
    d.build_dir = "."
    d.has_ssh = true
  end
  config.ssh.port = 22
end
