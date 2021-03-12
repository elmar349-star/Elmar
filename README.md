## Shadowsocks-libev with v2ray-plugin installer
This shell help you install shadowsocks listening on port 443 with v2ray-plugin.  
### Introduction
Install [shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev) and [v2ray-plugin](https://github.com/shadowsocks/v2ray-plugin).  
Get a certificate from [Let’s Encrypt](https://letsencrypt.org) to enable shadowsocks over websocket (HTTPS).  
You must use shadowsocks via port 443 with v2ray-plugin and can even run your shadowsocks server behind the CDN like [Cloudflare](https://www.cloudflare.com/).  
### Requirement
VPS  
You can sign up through my referral link:  
[Vultr](https://www.vultr.com/?ref=8382242-6G), [DigitalOcean](https://m.do.co/c/7ea2fecf9223), [Linode](https://www.linode.com/?r=69960c4818028406de98ad12d7a19913869992e1), [CloudCone](https://app.cloudcone.com/?ref=1365)  
Domain  
You can register one for free at [freenom](https://my.freenom.com/clientarea.php).  
Point your domain to the IP address with A record.  
### Usage
```bash
# Installation
## Ubuntu 18.04/16.04 or Debian 9/10
wget -O ubuntu-ss-install.sh https://github.com/M3chD09/shadowsocks-with-v2ray-plugin-install/raw/master/ubuntu-ss-install.sh
chmod +x ubuntu-ss-install.sh
./ubuntu-ss-install.sh

# Manage shadowsocks with systemctl
systemctl status shadowsocks
systemctl start shadowsocks
systemctl stop shadowsocks
```
### Notice
Tested on Ubuntu 18.04
***Full of bugs.**
