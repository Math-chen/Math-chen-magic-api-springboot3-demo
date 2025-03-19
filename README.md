修复分2部分：


1）在自己的magicapi项目中添加
org.ssssssss.magicapi中的所有类（修复了新特性不兼容的问题）

![img.png](img.png)

2）在pom.xml中添加如下配置，编译时增加这个参数，方便spring获取参数名
![img_1.png](img_1.png)