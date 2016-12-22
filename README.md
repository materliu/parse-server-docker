Parse Server 用来快速部署一个后端服务， 给前端调用， 释放我们的开发量

Parse Server is an open source version of the Parse backend that can be deployed to any infrastructure that can run Node.js. 

link: https://github.com/ParsePlatform/Parse-Server

注意修改 

docker-compose.yml 文件中的 
 * SERVER_URL: http://*****:1337/parse
 * PARSE_DASHBOARD_SERVER_URL: http://*****:1337/parse  这两个地址保持一致即可 
 * APP_ID
 * MASTER_KEY
 * 所有 dingfu*** dingfu_*** 的值

JS 如何调用 parse后端服务， 详见项目下代码： sample-js

SDK 的学习资料见： https://parseplatform.github.io/#sdks

API 文档： https://parseplatform.github.io/Parse-SDK-JS/api/classes/Parse.Config.html