myaf
====

基于php-yaf框架，加入一些类库


可以按照以下步骤来部署和运行程序:                                                     
1.请确保机器root@AY140312100419468145Z已经安装了Yaf框架, 并且已经加载入PHP;
2.把myaf目录Copy到Webserver的DocumentRoot目录下;
3.需要在php.ini里面启用如下配置，生产的代码才能正确运行：
yaf.environ="product"
4.重启Webserver;
5.访问http://yourhost/myaf/,出现Hellow Word!, 表示运行成功,否则请查看php错误日志;""
