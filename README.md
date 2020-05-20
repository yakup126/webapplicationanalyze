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
__        __   _       _                _ _           _   _
\ \      / /__| |__   / \   _ __  _ __ | (_) ___ __ _| |_(_) ___  _ __
 \ \ /\ / / _ \ '_ \ / _ \ | '_ \| '_ \| | |/ __/ _` | __| |/ _ \| '_ \
  \ V  V /  __/ |_) / ___ \| |_) | |_) | | | (_| (_| | |_| | (_) | | | |
   \_/\_/ \___|_.__/_/   \_\ .__/| .__/|_|_|\___\__,_|\__|_|\___/|_| |_|
                           |_|   |_|
    _                _
   / \   _ __   __ _| |_   _ _______
  / _ \ | '_ \ / _` | | | | |_  / _ \
 / ___ \| | | | (_| | | |_| |/ /  __/
/_/   \_\_| |_|\__,_|_|\__, /___\___|
                       |___/

                                                              
Scan Started...
---------------Subdomain Scaning Started-----------------</br>
[*]Tried: 2386\31218  :http://besmd.instagram.com</br>
[+]Found: 2387\31218  :http://i.instagram.com                                                       
----------------Hidden Url Scaning Started-----------------
[*]Tried : 6521\59345 :http://instagram.com/homes
[+]Found : 6522\59345 :http://instagram.com/accounts/login/
[*]Tried : 6533\59345 :http://instagram.com/Kayit.php
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
<b1>Warning : Sometimes it doesn't work, try again</b1></br>
My English is not very good so i might have made mistake
