### 1. Change to sudo **
```
sudo su -
```
#
### 2. Get the install script **
```
wget https://raw.githubusercontent.com/hestiacp/hestiacp/release/install/hst-install.sh
```
#
### 3. Important - CHANGE THE NEXT LINE TO USE YOUR OWN DETAILS, recommend using a subdomain like 'hcp' for your panel as I've done here **

```
bash hst-install.sh --interactive no --email admin@example.com --password exampledemopassword --hostname hcp.example.com -f
```
#
### After its done, reboot with: **
```
reboot
```
#
### Add Ports
```
8083,80,443,143,993,110,995,25,465,587
```
#
### Visit your Site on
```
http://you-server-ip:8083/login/
```
