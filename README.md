# SSH Reverse Tunnel

## Description

Using autossh and reverse ssh tunneling to enable accessing your machines even if they are NAT'd or behind firewalls - automatically.

How to use this:

(Note this script assumes you are using Ubuntu)

## 1. Update server

```bash
apt update && apt upgrade -y

```

## 2. Download script on server

```bash
wget https://raw.githubusercontent.com/iPmartNetwork/reverse_ssh_tunnel/main/setup_reverse_tunnel.sh
```

## 3.Chmod script

```bash
chmod +x ./setup_reverse_tunnel.sh
```

## 4.Run script

```bash
sudo ./setup_reverse_tunnel.sh
```
