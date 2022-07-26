#### mysql死锁
https://wenku.baidu.com/view/82e96f842b4ac850ad02de80d4d8d15abe230002.html

#### MySQL InnoDBでのネクストキーロックの落とし穴
http://tech.voyagegroup.com/archives/523885.html

show variables like 'general_log%';
select event_time, convert(argument using utf8) from mysql.general_log where event_time between '2022-07-22' and '2022-07-23' limit 20;
