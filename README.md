# donscripts

## 3proxy
`bash 3proxy.sh`

Add auth method, iponly for ip white list, strong for user & password

`auth iponly strong`

Change the user and password bellow

`users user:CL:password`

Change ip1/ip2 to ips passed

`allow * ip1,ip2 * *`

Change user

`allow user`

Add multi ips

add bellow
```
# comment socks -p1080
# socks -p1080
# add ip per line as bellow, change $ip1 to ip, such as 192.168.168.1
socks -p1080 -i$ip1 -e$ip1
socks -p1080 -i$ip2 -e$ip2
```

Run `bash 3proxy_restart.sh`
