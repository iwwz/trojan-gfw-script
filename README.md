![logo](https://raw.githubusercontent.com/johnrosen1/trojan-gfw-script/master/logo.png)
# VPS Toolbox

VPSToolBox is a bash script that helps you setup Trojan-gfw Nginx Hexo Netdata and other powerful applications on a Linux server really quickly.

[![Gitter](https://badges.gitter.im/vpstoolbox/community.svg)](https://gitter.im/vpstoolbox/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

#### How to use([中文版](https://github.com/johnrosen1/vpstoolbox/blob/master/docs/README_zh_cn.md))
```
apt-get update && apt-get install sudo curl -y && curl -Ss https://raw.githubusercontent.com/johnrosen1/vpstoolbox/master/vps.sh | sudo bash
```

Flowchart:
![flowchart](https://raw.githubusercontent.com/johnrosen1/vpstoolbox/master/images/flowchart.png)

#### Privacy Statement:

Ip Information is just an indispensable part of this project, all ip information comes from ipinfo.io,no spam related.

#### Friendly Reminder:
1. Please **Run as root**(sudo -i)
2. Please **[Purchase a domain](https://www.namesilo.com/?rid=685fb47qi)** and **[finish a dns resolve](https://dnschecker.org/)** before running this program!
3. Please **Open Tcp port [80](https://www.speedguide.net/port.php?port=80) and [443](https://www.speedguide.net/port.php?port=443) and turn off Cloudflare CDN** in your control panel before running this program!
4. For customized certificate , please put it in /etc/trojan/ , no name change required !
5. Please use a VPS with more than **0.5 GB RAM** and at least **5G FREE DISK SPACE**. 

#### Features:

1. Auto install and config **[NGINX](https://www.nginx.com/)**
2. Support all kinds of virtualization including kvm openvz and so on.
20. Support Auto install and config **[Trojan-GFW](https://github.com/trojan-gfw/trojan) [Hexo](https://hexo.io/zh-tw/docs/) [Dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) [Qbittorrent](https://www.qbittorrent.org/) [Bittorrent-Tracker](https://github.com/webtorrent/bittorrent-tracker) [Aria2](https://github.com/aria2/aria2) [Filebrowser](https://github.com/filebrowser/filebrowser) [Netdata](https://github.com/netdata/netdata) [MariaDB](https://mariadb.org/) [PHP](https://www.php.net/) RSSHUB [Tiny Tiny RSS](https://git.tt-rss.org/fox/tt-rss) Fail2ban [TOR](https://famicoman.com/2018/01/03/configuring-and-monitoring-a-tor-middle-relay/) [Speedtest](https://github.com/librespeed/speedtest) [Trojan-panel](https://github.com/trojan-gfw/trojan-panel) Postfix Dovecot Roundcube-Webmail**
3. Auto issue and renew [let's encrypt certificate](https://letsencrypt.org/) and auto reload Trojan-GFW after renewal
4. **Support [Debian](https://www.debian.org/) [Ubuntu](https://ubuntu.com/)**
17. [Full IPv6 Support](https://en.wikipedia.org/wiki/IPv6)
17. [Full HTTP/2 Support](https://en.wikipedia.org/wiki/HTTP/2)
18. [time sync](https://www.freedesktop.org/software/systemd/man/timedatectl.html)
19. Fail Restart
20. [uninstall Aliyun Aegis](https://www.johnrosen1.com/ali-iso/)
9.  Support [TCP Turbo](https://github.com/shadowsocks/shadowsocks/wiki/Optimizing-Shadowsocks)
15. Support [TLS1.3 ONLY](https://wiki.openssl.org/index.php/TLS1.3)
23. Support Full/Part Uninstall
24. And so on...

### Give it a try ! (Live Demo,no Guarantee)

[https://trojan-gfw.xyz/vpstoolbox/](https://trojan-gfw.xyz/vpstoolbox/)

## If you found it useful , please give a star ,thanks!

## License

[MIT](https://github.com/johnrosen1/vpstoolbox/blob/master/LICENSE)


## Stargazers over time

[![Stargazers over time](https://starchart.cc/johnrosen1/vpstoolbox.svg)](https://starchart.cc/johnrosen1/vpstoolbox)

***Please do not use vultr to run this project !***
