Vagrant.configure("2") do |config|
  config.vm.box = "fedora/37-cloud-base"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end
end
