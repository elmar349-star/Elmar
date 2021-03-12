## Shadowsocks-libev with v2ray-plugin installer
This shell help you install shadowsocks listening on port 443 with v2ray-plugin.  
### Introduction
Install [shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev) and [v2ray-plugin](https://github.com/shadowsocks/v2ray-plugin).  
Get a certificate from [Let’s Encrypt](https://letsencrypt.org) to enable shadowsocks over websocket (HTTPS).  
You must use shadowsocks via port 443 with v2ray-plugin and can even run your shadowsocks server behind the CDN like [Cloudflare](https://www.cloudflare.com/).  
### Requirement
VPS

domain

Cloudflare
### Usage
```bash
# Installation
## Ubuntu 18.04/16.04 or Debian 9/10
wget -O ubuntu-ss-install.sh https://raw.githubusercontent.com/elmar349-star/Shadowsocks-ubuntu-installer/main/ubuntu-shadowsocks-install.sh
chmod +x ubuntu-ss-install.sh
./ubuntu-ss-install.sh

# Manage shadowsocks with systemctl
systemctl status shadowsocks
systemctl start shadowsocks
systemctl stop shadowsocks
```
### Notice
Tested on Ubuntu 18.04/16.04
***Full of bugs.*** 
