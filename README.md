# ssm-demo
this is my ssm-demo
����ڸ�ϰssm���֪ʶ������һ���ܼ򵥵�ssm��ܡ�

�õ���MySQL���ݿ��Լ����Խ�һ�����û�����������applicationContext.xml�Լ����á�

������
create database how2java;


����׼����Categoryֻ��2���ֶ�
use how2java;
  
CREATE TABLE category_ (
  id int(11) NOT NULL AUTO_INCREMENT,
  name varchar(30) ,
  PRIMARY KEY (id)
) DEFAULT CHARSET=UTF8;




��㽨һЩ���ݡ�
use how2java;
   
insert into category_ values(null,"category1");
insert into category_ values(null,"category2");
insert into category_ values(null,"category3");
insert into category_ values(null,"category4");
insert into category_ values(null,"category5");
 
select * from category_
