# PHP-DDoS-Protect
Simple DDoS Protect for PHP &amp; Apache

-Installing-

1- Upload all files your FTP Server.

2- Enter this code on all pages.

  - "include("global.php");"

-Customization-

  - Open global.php and replace "if($_SESSION['last_session_request'] > time() - 2){" to "if($_SESSION['last_session_request'] > time() - second){".
  - Change the folder's name. (Protect)
  - Open Protect/.htaccess and replace "ErrorDocument 403 /protect/403.shtml" to "ErrorDocument 403 /customdirectory/403.shtml".
  - Open /.htaccess and replace "RewriteRule ^access_denied$  protect/index.php$1 [L,QSA]" to "RewriteRule ^access_denied$  customdirectory/index.php$1 [L,QSA]"
  - Open 403.shtml and edit. (optional)
