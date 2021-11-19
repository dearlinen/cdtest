# cdtest

使用GitHub Actions实现CI/CD流程的模板仓库

流程为将项目打包后推送到服务器

仓库中的vue工程文件仅为测试，并无实际意义

## 使用方法

fork本仓库，在`secrets`选项里配置私有变量，变量有固定的名称

|变量名|作用|
|:----    |:-------    |
|DEPLOY_KEY    |服务器的私钥     |
|SERVER_IP |服务器的IP地址 |
|SERVER_PORT |服务器的SSH端口 |
|SERVER_USERNAME     |登录到服务器的用户名 |
|SERVER_PATH|部署到服务器的路径     |
