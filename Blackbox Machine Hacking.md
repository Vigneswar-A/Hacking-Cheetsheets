### TCP SCAN
```shell
sudo nmap 10.129.1.5 -Pn -sC -sV --min-rate 1000 -p- --open
```

### UDP SCAN
```shell
sudo nmap 10.129.1.5 -sU --min-rate 1000 --open
```

### ADD VHOST
```shell
echo '10.129.1.5 variatype.htb' | sudo tee -a /etc/hosts
```
