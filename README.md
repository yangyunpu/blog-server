## 简介


基于node.js、koa、koa-router、koa-body、seqlize、mysql、bcryptjs、nodemon等主流技术


## 运行

```git
# npm 版本 v6.14.17
# node 版本 v16 v18 都可以


1、打开项目，安装依赖
npm i
2、数据库是mysql，需要先连接数据库
应该大家都有mysql吧，没有就装一个，再装个navicat
(1) 打开项目，在根目录下找到src文件夹下的db文件夹，里面有数据库的sql文件
(2) 使用navicat创建一个空的数据库，运行这个sql文件，就可以生成表
(3) 打开项目根目录下的.env文件，根据注释修改自己的mysql数据库账号名称、密码进行连接即可
3、运行项目 
npm run serve 

tips：.env文件下可以配置项目的上传文件方式，local为本地上传，qiniu为上传到七牛云存储,online为上传到自己的云服务器。
```
