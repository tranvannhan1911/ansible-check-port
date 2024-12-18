# ansible-check-port

Example output

```
TASK [Display port check results] **********************************************************************************************************************************************************************
ok: [fcd_server_01] => (item={'host': 'google.com', 'port': 80, 'rc': 0, 'stderr': 'Connection to google.com (142.250.196.238) 80 port [tcp/http] succeeded!'}) => {
    "msg": "Success"
}
failed: [fcd_server_01] (item={'host': 'jakjsajkexample.com', 'port': 80, 'rc': 1, 'stderr': 'nc: getaddrinfo for host "jakjsajkexample.com" port 80: Name or service not known'}) => {
    "msg": "Failed"
}
```