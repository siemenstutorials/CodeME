# CodeME
Brook
````bash
wget -qO brook-pf-mod.sh https://raw.githubusercontent.com/siemenstutorials/brookf/master/brook-pf-mod.sh && chmod +x brook-pf-mod.sh && bash brook-pf-mod.sh
````
Brook Config
````bash
vi /usr/local/brook-pf/brook.conf
````
V2b
````bash
bash <(curl -Ls https://raw.githubusercontent.com/siemenstutorials/SPanel/master/vturay.sh)
````
Socks5
````bash
bash <(curl -Ls https://raw.githubusercontent.com/siemenstutorials/Socks5Go/master/install.sh)
````
Gost
````bash
wget --no-check-certificate -O gost.sh https://raw.githubusercontent.com/siemenstutorials/GTSK5/master/gost.sh && chmod +x gost.sh && ./gost.sh
````
L2TP
````bash
bash <(curl -Ls https://raw.githubusercontent.com/siemenstutorials/L2tp/master/VPN.sh)
````
Linux路由
````bash
echo net.ipv4.ip_forward=1>>/etc/sysctl.conf
sysctl -p
````
BT国际
````bash
yum install -y wget && wget -O install.sh http://www.aapanel.com/script/install_6.0_en.sh && bash install.sh
````
GostHTTPStoSocks
````bash 
bash <(curl -Ls https://raw.githubusercontent.com/siemenstutorials/GTSK5/master/GostoSk5.sh)
````
PID Delte
````bash
mkdir -p /var/run/ss5   #PID删除
iptables -nvL -t nat
iptables -nvL -t mangle  #转发查询
````
BBR原版
````bash
wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh && chmod  +x bbr.sh && ./bbr.sh
````

逗B SSR
````bash
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
````
Hd to SK5
````bash
nohup ./gost -L=:45100 -F=name:password@ip:port &

# vi startup.sh
# #!/binbash
#nohup ./gost -L=:4900 -F=name:password@ip:port >> /dev/null 2>&1 &

````
Host ADD
````bash 
echo "185.199.109.133 raw.githubusercontent.com" >> /etc/hosts
echo "140.82.112.3 github.com" >> /etc/hosts
````
回国一键
````bash
bash <(curl -Ls https://raw.githubusercontent.com/siemenstutorials/shadowsocksbackup/master/Sgo.sh)
````
GOST SK5
````bash
bash <(curl -Ls https://raw.githubusercontent.com/siemenstutorials/GTSK5/master/GoToSocks5.sh)
````
GostTOsk5自动重启
````bash
crontab -e
@reboot /root/startup.sh

vi startup.sh
#!/bin/bash
nohup ./gost -L s1:hikelin@:3316 socks5://:3316 >> /dev/null 2>&1 &
echo "GostSk5重启完成"
````

SK5一键
````bash
bash <(curl -Ls https://raw.githubusercontent.com/siemenstutorials/MutiPxray/master/Singleport.sh)
````


































