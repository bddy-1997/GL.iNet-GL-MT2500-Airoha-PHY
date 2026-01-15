## GL.iNet GL-MT2500 Airoha PHY

```
autocore base-files block-mount bridger ca-bundle default-settings-chn dnsmasq-full dropbear firewall4 fitblk fstools kmod-crypto-hw-safexcel kmod-gpio-button-hotplug kmod-leds-gpio kmod-nf-nathelper kmod-nf-nathelper-extra kmod-nft-offload kmod-phy-aquantia libc libgcc libustream-openssl logd luci-app-package-manager luci-compat luci-lib-base luci-lib-ipkg luci-light mtd netifd nftables odhcp6c odhcpd-ipv6only opkg ppp ppp-mod-pppoe procd-ujail uboot-envtools uci uclient-fetch urandom-seed urngd wpad-openssl -wpad-openssl e2fsprogs f2fsck mkf2fs kmod-usb3 kmod-phy-airoha-en8811h airoha-en8811h-firmware automount luci-app-argon-config luci-i18n-argon-config-zh-cn luci-i18n-package-manager-zh-cn luci-i18n-ttyd-zh-cn luci-i18n-samba4-zh-cn script-utils
```
安装istore
```
wget -qO imm.sh https://cafe.cpolar.cn/wkdaily/zero3/raw/branch/main/zero3/imm.sh && chmod +x imm.sh && ./imm.sh
```
安装首页与网络向导
```
is-opkg install luci-i18n-quickstart-zh-cn
```
