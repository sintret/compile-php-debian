# compile-php-debian

$ git clone https://github.com/sintret/compile-php-debian.git
$ cd compile-php-debian

# ./install_php.sh 7.1.0
FOR PHP VERSION 7.1.8 RUN
# ./install_php.sh 7.1.8 

# service php7-fpm start
# service php7-fpm status
[ ok ] php-7.1.0-fpm is running.

# cgi-fcgi -bind -connect 127.0.0.1:9000
X-Powered-By: PHP/7.1.0
Content-type: text/html; charset=UTF-8
