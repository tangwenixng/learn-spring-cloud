# 演示配置中心的使用

注意：github 默认创建分支名称是main(以前是master),所以需要手动创建分支

浏览器中访问：http://localhost:9000/application/master
或者 http://localhost:9000/client/dev/master
可获取配置文件内容

访问配置信息的URL与配置文件的映射关系如下：

/{application}/{profile}[/{label}]
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties