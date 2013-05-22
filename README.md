vagrant-node-mongo-redis
========================

Vagrant Box and Vagrant File for node.js (with npm and express), mongodb and redis in one 64-bit box.

# Setup Instructions

0. Create an empty workspace directory, say 'scratch'
0. cd scratch
0. git clone https://github.com/biren/vagrant-node-mongo-redis.git
0. cd vagrant-node-mongo-redis
0. vagrant init myvm vagrant-node-mongo-redis-64.box
0. mv Vagrantfile old.Vagrantfile
0. mv new.Vagrantfile Vagrantfile
0. edit Vagrantfile and change line config.vm.box = "vagrant-node-mongo-redis-64" with the name you gave in vagrant init step (e.g. myvm)
0. vagrant up
