--表空间
create tablespace base
datafile 'e:\oracle\oradata\orcl\base.dbf' size 500m  
autoextend on next 50m 
maxsize unlimited

--drop tablespace base2016 including contents and datafiles;
--2.建用户
create user base 
identified by hhh  
default tablespace base;
 
 
 grant connect,resource,dba to base;
