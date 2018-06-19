# javaee01
taotao商城test
本项目是分布式开发和soa开发，属于本人在学习阶段的练手项目，希望不要笑话。
项目目前正处于开发阶段，会定期上传更新。
我将项目分为了四个子系统，分别是父系统，公共应用系统，后端管理系统，和前端系统。目前只是搭了个框架，熟悉各系统的依赖关系。
common，manager，manager-web都继承parent，manager,manager-web都依赖common
manager又分为dao,pojo,interface,service四个模块
dao，interface依赖pojo模块，service依赖dao模块.
