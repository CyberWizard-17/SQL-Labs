# SQL-Labs

#lab Setup

Just copy all the given files to your "htdocs" folder of the XAMMP directory.

ALSO, Copy paste these commands in your Xammp/Mysql/Bin Folder's CMD -

mysql -u root

create database w;


use w;

create table signin(id int, username varchar(100),password varchar(100),encpassword varchar(100),description varchar(100));


insert into signin values(1,"user","pass",md5("pass"),"Notes for user");

insert into signin values(2,"king","royal",md5("royal"),"Bio of the king");

insert into signin values(3,"name","letmein",md5("123"),"About name");

insert into signin values(4,"run","qwerty",md5("qwerty"),"Race details");


CREATE USER 'web'@'localhost' identified by 'P@ssw0rd';

GRANT ALL on * TO 'web'@'localhost';


That's all for the setup..
