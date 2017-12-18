# controller
I pick RYU as our main controller. Later, opendaylight might be implemented

openwrt package make method

git clone https://github.com/CPqD/openflow-openwrt.git

create soft link

~/openwrt/packages/openflow-1.3 -> ~/openwrt/openflow-openwrt/openflow-1.3

cd /home/tang/openwrt/openwrt/package/
ln -s /home/tang/openwrt/openwrt/openflow-openwrt/openflow-1.3/
~/openwrt/files -> ~/openwrt/openflow-openwrt/openflow-1.3/files

cd /home/tang/openwrt/openwrt
ln -s /home/tang/openwrt/openwrt/openflow-openwrt/openflow-1.3/files

and then using 'make menuconfig'

choose Network -> openflow


