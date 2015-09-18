
Vagrant.configure(2) do |config|
  
  config.vm.synced_folder '.', '/vagrant', disabled: true
  config.vm.box = "ricardson/slackware64-14.1-minimal"


  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "provisioning/site.yml"
  end





end
