Vagrant.configure(2) do |config|
  config.vm.define :lara_dev do |lara_dev|
    # Find your favorite os at:
    # https://atlas.hashicorp.com/boxes/search
    lara_dev.vm.box = 'centos/7'
    lara_dev.vm.network :private_network, ip: '192.168.80.80'
    lara_dev.vm.network :forwarded_port, guest: 80, host: 8000
  end
end
