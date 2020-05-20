# webapplicationanalyze
port scanner 
hidden url brute force
subdomains brute force
required : terminaltables, python3 , socket, requests
Usage: webpentester.py [options]

Options:
  -h, --help            show this help message and exit
  -u URL, --url=URL     enter url without http://
  -s SUBWORDLIST, --subwordlist=SUBWORDLIST
                        select subdomain wordlist file
  -a HIDDENWORDLIST, --hiddenurlwordlist=HIDDENWORDLIST
                        select hidden url wordlist file
results:

                                                                            
Scan Started...
---------------Subdomain Scaning Started-----------------
[*]Tried:http://i.instagram.com
[+]Found: http://i.instagram.com                                                       
----------------Hidden Url Scaning Started-----------------
[*]Tried : http://instagram.com/homes
[+]Found : http://instagram.com/accounts/login/
[*]Tried : http://instagram.com/Kayit.php
----------------Port Scaning Started-----------------
[*]Scanning Port:80
[+]Port 80: OPEN
[+]Port 443: OPEN

RESULTS:
                          
+--------------------------------------+--------------+-------+
| Host                                 | Scan Type    | Dest  |
+--------------------------------------+--------------+-------+
| http://i.instagram.com               | subdomain    | found |
| http://instagram.com/accounts/login/ | hidden url   | found |
|                                      |              |       |
| 3.226.111.93                         | Port Scanner | 80    |
+--------------------------------------+--------------+-------+
