# 一XRayR
A Xray backend framework that can easily support many panels.

一An Xray-based backend framework supporting V2ray, Trojan, and Shadowsocks protocols. It is highly extensible and supports multi-panel integration.

Find the source code here: [XrayRR/XrayR](https://github.com/iSiMX/XrayR)

If you are not sure about the script, you can test it in this sandbox before using it. ：https://killercoda.com/playgrounds/scenario/ubuntu

一一一一一一一一一一一一
# GitBook

[Help](https://xrayrr.gitbook.io/xrayr-doc/)

一一一一一一一一一一一一
# 一Installer

```
bash <(curl -Ls https://raw.githubusercontent.com/iSiMX/XrayR-script/master/install.sh)
```
OR
```
wget -N https://raw.githubusercontent.com/iSiMX/XrayR-script/master/install.sh && bash install.sh
```

一一一一一一一一一一一一
# 一 Upload V0.9.0 To Root Ubuntu

```
apt install wget unzip -y
wget https://github.com/iSiMX/XrayR-script/releases/download/V0.9.0/XrayR.zip
unzip XrayR.zip
rm -fr /usr/local/XrayR/XrayR
mv XrayR /usr/local/XrayR/
chmod +x /usr/local/XrayR/XrayR
```
