配置启动参数

Main class设置为org.apache.catalina.startup.Bootstrap

添加VM options 
-Dcatalina.home=catalina-home    -Dcatalina.base=catalina-home  -Djava.endorsed.dirs=catalina-home/endorsed  -Djava.io.tmpdir=catalina-home/temp  -Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager  -Djava.util.logging.config.file=catalina-home/conf/logging.properties


需要稍微调下源码才能运行起来
https://blog.csdn.net/yekong1225/article/details/81000446