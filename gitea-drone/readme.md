# 功能

启动源代码管理工具(gitea)及CD工具(Drone)，可以很方便的将Devops集成到项目中

# 更改配置

1. 替换yml档案中changeme的内容

# 启动

使用如下命令一键启动：

    docker-compose up -d

# 测试

1. 测试 gitea ： curl localhost:8001
2. 测试 drone : curl localhost:8002

# 参考

* [gitea image](https://hub.docker.com/r/gitea/gitea/)
* [Installation with Docker](https://docs.gitea.io/en-us/install-with-docker/)