# SCRIPTMULTIPLUS
# cmdtunel

# CMD AWAL
```
echo -e "net.ipv6.conf.all.disable_ipv6 = 1\nnet.ipv6.conf.default.disable_ipv6 = 1\nnet.ipv6.conf.lo.disable_ipv6 = 1" >> /etc/sysctl.conf && sysctl -p
```
```
apt update -y && apt upgrade -y --fix-missing && apt install curl jq wget screen build-essential -y && update-grub && apt dist-upgrade -y && sleep 2 && reboot
```

# CMD INSTALASI
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && \
sysctl -w net.ipv6.conf.default.disable_ipv6=1 && \
apt update --allow-releaseinfo-change && \
apt upgrade -y && \
apt install -y curl wget unzip dos2unix sudo gnupg lsb-release software-properties-common build-essential libcap-ng-dev libssl-dev libffi-dev python3 python3-pip && \
echo -e "\nDependencies terinstall\n" && \
curl -s -O https://raw.githubusercontent.com/indrisetyani987/SCRIPTMULTIPLUS2/main/install.sh && \
chmod +x install.sh && \
screen -S install ./install.sh
```

CMD INSTALASI UDP UNLI
```
apt update -y && wget -q https://raw.githubusercontent.com/indrisetyani987/SCRIPTMULTIPLUS/main/zivpn.sh -O /usr/local/bin/zivpn-manager && chmod +x /usr/local/bin/zivpn-manager && /usr/local/bin/zivpn-manager
```

izin 1
https://github.com/indrisetyani987/SCRIPTMULTIPLUS/blob/main/register

izin 2
https://github.com/indrisetyani987/SCRIPTMULTIPLUS/blob/main/register2
