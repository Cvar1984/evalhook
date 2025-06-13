http://php-security.org/2010/05/13/article-decoding-a-user-space-encoded-php-script/index.html

phpize && ./configure && make

php -d extension=evalhook.so encoded_script.php

for php 8 use [eval-logger](https://github.com/Cvar1984/eval-logger)
