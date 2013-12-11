# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!


VAGRANTFILE_API_VERSION = "2"

BOX_NAME = ENV['BOX_NAME'] || 'precise-docker'
BOX_URI = ENV['BOX_URI'] || 'http://bit.ly/dockerprecise64'

Vagrant.require_version '>= 1.4.0'

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

    config.vm.box = BOX_NAME
    config.vm.box_url = BOX_URI

    config.vm.network :private_network, ip: '192.168.66.66'

end
