# mysql 5.7.17修改密码

查找初始密码
>  #: cat /var/log/mysql.log |grep temp

>  #: mysql -uroot -p

>  #: alter user 'root'@'localhost' identified by 'Cit1218!@#$%^';

远程访问

grant all privileges on *.* to 'root'@'172.24.%' identified by 'Ctv1218!@#$%^' with grant option;

