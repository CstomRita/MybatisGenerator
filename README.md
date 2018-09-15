# Mybatis逆向工程

修改mybatis-generator-config.xml中：

1 JDBC 数据库连接部分

2 pojo、mapper.java、mapper.xml的targetpackage并在相应位置创建包

3 修改tableName,tabelName必须和数据库中表名称一一对应不可写错

如果希望insert之后返回主键可以在table里设置主键，如果不需要可以不设置

4 修改完成之后，IDEA——Maven Plugin -generator run即可

5 生成POJO等文件后将其拷贝到自己的工程便可