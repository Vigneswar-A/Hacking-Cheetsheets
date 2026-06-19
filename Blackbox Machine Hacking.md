```shell
sudo bash -c 'nmap 10.129.1.5 -sS -sU -Pn -sC -sV --min-rate 1000 -p T:1-65535,U:1-6000 --open' 2>/dev/null
```
