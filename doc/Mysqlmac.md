## 修改密码

```
cd /usr/local/mysql/bin/
sudo su
./mysqld_safe --skip-grant-tables &

./mysql

mysql> FLUSH PRIVILEGES
mysql> SET PASSWORD FOR 'root'@'localhost' = PASSWORD('123456');
```
