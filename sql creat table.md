# 数据库建表语句:smile::
create table table_name
(
  id int primary key,
  name varchar(255),
  othertable_id int,
  contstraint othertable foreign key(othertable_id) references(id)
)