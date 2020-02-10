# mysql-with-API
create database Empdata;
use Empdata;
create table user(userid int not null auto_increment,username varchar(100) not null,password varchar(100) not null,primary key(userid));
insert into user(username,password) value("arifa","arifa");
select * from user;
