First of all set up academy on your VM ware

![](https://i.imgur.com/sqlEL3g.png)

Now use the logs `root:tcm` and you should be logged in successfully, Once logged in you can use the command `dhclient` followed by `ip a` to check for machine ip address

![](https://i.imgur.com/oVlP40y.png)

Time to run our Nmap scan on targets, first of all directly SSH to the target using the host system to make things easier for us to interact with the Machine instead of clicking VM Ware always

![](https://i.imgur.com/cTGXvph.png)

![](https://i.imgur.com/aGx2Ruw.png)

If you have problems connecting, Make sure to set network to bridge then run `dhclient` before `ip a` 

Running our Nmap scan , Query `nmap -p- -sCV 192.168.0.108 -v --min-rate=1000 -T4 -oN nmap_academy.txt`

![](https://i.imgur.com/v6wqzFu.png)

> Usually i
## Enumeration



