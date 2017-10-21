# Linux知识

## 端口放行
iptables -I INPUT -p tcp --dport 80 -j ACCEPT

iptables-save

## 