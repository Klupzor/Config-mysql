# Config-mysql

1- Run first the scrip to config AirBnB clone enviroment

2- cat setup_mysql_dev.sql | mysql -hlocalhost -uroot -p

3- echo "SHOW GRANTS FOR 'hbnb_dev'@'localhost';" | mysql -uroot -p

4- curl -o 100-dump.sql "https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/290/100-hbnb.sql"

5- cat 100-dump.sql | mysql -uroot -p
