
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://sosad87.github.io/test/index.html$1 [R,L]
