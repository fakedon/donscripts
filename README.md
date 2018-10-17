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

Run `bash 3proxy_restart.sh`
