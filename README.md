AcrylicHosts
============

利用Acrylic DNS Proxy搭建自己的dns服务。
#配置Acrylic DNS Proxy
安装软件后，将AcrylicConfiguration.ini和AcrylicHosts.txt替换原来的文件即可。
将dns服务器地址改为127.0.0.1
#原理
先解析符合AcrylicHosts.txt规则中的域名
有，直接返回地址
没有，交给114.114.114.114解析。
hosts文件不支持通配符，软件Acrylic DNS Proxy可以解决通配符的问题，可以正常访问google的各项服务。
