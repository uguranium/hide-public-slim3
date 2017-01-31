# Hide Public from Url
Hide a "public" from the url Slim framework 3

**Slim framework main directory  ./public** Create a htaccess.

>.htaccess

```
RewriteEngine on
RewriteCond %{REQUEST_FILENAME} !index.php
RewriteRule ^(.*)$ public/$1 [L]
```
