# brcmfmac4366c

Ps:适用于斐讯K3的LEDE/OpenWrt替换无线驱动(如果当前驱动足够稳定,没必要替换)

| 驱动 | 说明 |
| :----: | :----: |
| brcmfmac4366c-pcie.bin_ac88.48260 | 提取ac88u固件3.0.0.4.386.48260的驱动 |
| brcmfmac4366c-pcie.bin_ac88_3 | 2020-03-12的ac88u固件提取,也是大雕lean源码自带的驱动 |
| brcmfmac4366c-pcie.bin_ac88_2 | 2019-07-23的ac88u固件提取 |
| brcmfmac4366c-pcie.bin_ac88_1 | 2016-09-12的ac88u固件提取 |
| brcmfmac4366c-pcie.bin_r8500 | 2016-06-28的r8500的LEDE固件提取 |
| brcmfmac4366c-pcie.bin_ea9500_175339 | ea9500 v1.1.7.175339固件提取 |
| brcmfmac4366c-pcie.bin_ea9500_179240 | ea9500 v1.1.7.179240固件提取 |
| brcmfmac4366c-pcie.bin_k3 | k3原厂,不支持密码,切记!!! |
| brcmfmac4366c-pcie.bin_asus-dhd24 | ASUS 382.dhd24.ko提取 |
| brcmfmac4366c-pcie.bin_69027 | 匿名,听说很nice! |




怎么替换驱动?

1.WinSCP等软件登录进路由器

2.进到/lib/firmware/brcm/目录

3.将brcmfmac4366c-pcie.bin改成brcmfmac4366c-pcie.bin.bak

4.将你要替换的驱动传到/lib/firmware/brcm/目录

5.然后将替换进去的驱动改名成brcmfmac4366c-pcie.bin

6.重启路由

