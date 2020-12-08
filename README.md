# Vulnhub-JISCTF-WebDir
This repo contains the modified code &amp; files of web directory (/var/www/html ) of vulnerable JIS-CTF from Vulnhub. 
Orignal VM: https://www.vulnhub.com/entry/jis-ctf-vulnupload,228/

*Spoiler Alert*

Notable modifications I have done:
1. Removed information from robots.txt & removed web user credentials that were hidden in the source code of HTML.
2. User credentials present in a random /var/www/html directory.
3. Javascript file validation, only image files are allowed to be uploaded to server. (index.php)
4. Giving 777 permssion to uploaded files. (index.php)
