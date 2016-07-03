# PHP-DDoS-Protect
Simple DDoS Protect for PHP &amp; Apache

-Installing-

1- Upload all files your FTP Server.

2- Enter this code on all pages.

  - "include("global.php");"

-Customization-

  - Change the folder's name (Protect)
  - Open .htaccess and replace "ErrorDocument 403 /protect/403.shtml" to "ErrorDocument 403 /customdirectory/403.shtml"
