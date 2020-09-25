# pierced
钉钉内网穿透

TCP 穿透需要在数据库里面执行：
GRANT ALL PRIVILEGES ON *.* TO root@'%' IDENTIFIED BY '123456';
FLUSH PRIVILEGES;
数据库连接命令：
mysql -h vaiwan.com -u root -p -P 1234 //端口号地址

bat 文件
ding -config=ding.cfg -subdomain=*** ****

 ding -config=ding.cfg -subdomain=etfse 192.168.236.250:8980
