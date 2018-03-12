# ssh-ngrok
使用ssh 实现花生壳代理

把远程服务器映射到本地端口

Welcome to the ssh- wiki!

在pi上安装openvpn
 
需要走vpn 

sudo openvpn /etc/openvpn/asdads.ovpn

ssh -N -f -R 2222:127.0.0.1:22 ceshi@10.0.0.115

ssh -CqTfnN -o TCPKeepAlive=yes -o ServerAliveInterval=60 -R 2222:127.0.0.1:22 ceshi@10.0.0.115

ServerAliveInterval 60

在115上 ssh -p 2222 pi@localhost 延伸 http://bencane.com/2017/04/15/using-stunnel-and-tinyproxy-to-hide-http-traffic/


