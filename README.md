# webapplicationanalyze
port scanner </br>
hidden url brute force</br>
subdomains brute force</br>
required : terminaltables, python3 , socket, requests</br>
Usage: webpentester.py [options]</br>
<pre>
Options:</br>
  -h, --help            show this help message and exit</br>
  -u URL, --url=URL     enter url without http://</br>
  -s SUBWORDLIST, --subwordlist=SUBWORDLIST</br>
                        select subdomain wordlist file</br>
  -a HIDDENWORDLIST, --hiddenurlwordlist=HIDDENWORDLIST</br>
                        select hidden url wordlist file</br>
results:</br>





                                                              
Scan Started...
---------------Subdomain Scaning Started-----------------</br>
[*]Tried:http://i.instagram.com</br>
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
                          
+--------------------------------------+--------------+---------+
| Host                                 | Scan Type    | Dest    |
+--------------------------------------+--------------+---------+
| http://i.instagram.com               | subdomain    | found   |
| http://instagram.com/accounts/login/ | hidden url   | found   |
|                                      |              |         |
| 3.226.111.93                         | Port Scanner | 80,443  |
+--------------------------------------+--------------+---------+
</pre>
</p>
<b1>Warning : Sometimes it doesn't work, try again</b1>
My English is not very good so i might have made mistake
