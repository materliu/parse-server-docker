Parse Server 用来快速部署一个后端服务， 给前端调用， 释放我们的开发量

Parse Server is an open source version of the Parse backend that can be deployed to any infrastructure that can run Node.js. 

link: https://github.com/ParsePlatform/Parse-Server

注意修改 docker-compose.yml 文件中的 SERVER_URL: http://10.211.55.4:1337/parse
      PARSE_DASHBOARD_SERVER_URL: http://10.211.55.4:1337/parse 选项

我们线上服务的 SERVER_URL是 parse.idingfu.cn 

JS 如何调用 parse后端服务， 详见项目下代码： sample-js