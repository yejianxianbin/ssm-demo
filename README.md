# ssm-demo
this is my ssm-demo
最近在复习ssm框架知识，这是一个很简单的ssm框架。

用到的MySQL数据库自己可以建一个。用户名和密码在applicationContext.xml自己设置。

建个表
create database how2java;


接着准备表Category只有2个字段
use how2java;
  
CREATE TABLE category_ (
  id int(11) NOT NULL AUTO_INCREMENT,
  name varchar(30) ,
  PRIMARY KEY (id)
) DEFAULT CHARSET=UTF8;




随便建一些数据。
use how2java;
   
insert into category_ values(null,"category1");
insert into category_ values(null,"category2");
insert into category_ values(null,"category3");
insert into category_ values(null,"category4");
insert into category_ values(null,"category5");
 
select * from category_
