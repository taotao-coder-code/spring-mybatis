# spring-mybatis
学生：spring连接mybtis的使用方法

在mybatis.xml设置别名，sql mapper(sql映射文件）的位置；
在applicationContext.xml中：创建dao接口的动态代理的对象；并且声明service,创建实现接口类的对象；然后调
用实现类中的方法；
spring和mybatis整合在一起使用，事务是自动提交的。 无需执行SqlSession.commit();
