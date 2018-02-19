# SFE
SFE 转发加速引擎设置

./scripts/feeds update -a

./scripts/feeds install -a

wget https://github.com/huaduxu/SFE/blob/master/sfe.patch

patch -p1 < sfe.patch

Select "kmod-fast-classifier"/"shortcut-fe-cm"/"shortcut-fe" under Kernel Modules > Network Support 
       "luci-app-sfe" under luci > luci app 
       > in Menuconfig
