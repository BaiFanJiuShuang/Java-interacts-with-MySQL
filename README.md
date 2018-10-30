# Java-interacts-with-MySQL
通过Java实现数据库表单查询、查询数据、添加数据、删除数据的功能
1.需要的驱动：
 Java程序连接MySQL需要mysql-connector-java驱动，我使用的是mysql-connector-java-5.1.39-bin.jar。
2. 项目结构：
Function.java是功能类，包含连接数据库、查询表单数据、删除表单数据、增加表单数据等功能。
test.java是测试类，调用Function中的功能方法，另外还有显示系统界面方法。
3. 数据库结构：
 用mysql -u root -p 密码  命令登陆数据库，show databases;显示数据库名称，use xiao7;选择xiao7数据库，show tables;显示xiao7数据库包含的表单，java程序都以xiao7数据库中的pre_xiaoqicommon_member表单为例。
4.总结：

  系统健壮性不够，如果遇到错误会直接终止，应该使用try catch抓取错误，报错和继续执行。
