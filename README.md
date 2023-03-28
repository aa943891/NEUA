# neua
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://aa943891.github.io/neua/index.html$1 [R,L]
