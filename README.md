# RancherOS

Download: rancheros.iso

sudo ros install -c https://raw.githubusercontent.com/WouterSpaans/RancherOS/master/cloud-config.yml -d /dev/sda

wget https://raw.githubusercontent.com/WouterSpaans/RancherOS/master/more-mounts.yml
vi more-mounts.yml
sudo ros config merge -i more-mounts.yml

