1、命令行输入 npm install -g json-server，安装json-server（安装了nodejs后才能使用npm命令）
2、创建文件db.json
3、命令行输入 json-server --watch db.json，启动服务（会显示url，可以访问资源）
关于Restful API的列表
GET     /posts      获取所有内容
GET     /posts/1    获取单个内容
POST    /posts      新增内容
PUT     /posts/1    更新内容
PATCH   /posts/1
DELETE  /posts/1    删除内容