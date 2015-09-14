
Vagrant.configure(2) do |config|

  config.vm.box = "ricardson/slackware64-14.1-minimal"


  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "provisioning/site.yml"
  end





end
