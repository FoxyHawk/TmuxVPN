# TmuxVPN

Combine openvpn, ssh and tmux for easy CnC client-server relationship.

## Install

Install/Update openvpn and tmux packages :
```
apt-get update
apt-get install openvpn tmux
```

Edit `ip.txt` to add your servers :
```
nano ip.txt
```

Using ssh-key with servers is recommended.

## Client Side

The host is multiple times client of different vpn servers.

## Server Side

`ip.txt` contains IP addresses of vpn servers.
