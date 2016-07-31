# mysql增删改查
	已经封装好的mysql增删改查的方法
	需安装MySQLdb

# EXAMPLE
	pip install MySQL-python
	
## code
	from m_mysql import * 
	my=mysql(host,username,password,database,port)
	my.query('select * from table1')
	my.select('select * from table1')
	
