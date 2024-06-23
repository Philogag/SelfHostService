
# SelfHostService - 自持服务部署模板

收集了一些常用服务的开源自持替代品

+ 使用 docker 进行集中管理
    + 使用 docker-compose 快速部署
    + 使用 docker volume 持久化用户数据，且方便对象存储
    + 使用 traefik 监听 docker label 实现子域名动态扩展


## 内容介绍

其中核心服务为必选，且必须按照顺序进行部署
业务服务可以按需进行部署

+ 核心服务
    + [x] [1. 核心子域名路由与SSL - Traefik](traefik)
    + [ ] [2. 单点登录 - Authelia / lldap ]()
    + [ ] [3. 数据备份 - Duplicati (可选)]()
+ 业务服务
    + 云端存储
        + [ ] [云盘 - NextCloud]()
        + [ ] [Git仓库 - Gitea]()
        + [ ] [照片库 - Immich]()
        <!-- + [ ] [媒体库]() -->
    + 信息管理
        + [ ] [密码管理 - Bitwarden]()
        + [ ] [记账 - Firefly-III]()
    + 下载管理
        + [ ] [Aria]()
        + [ ] [qBittorrent]()
    + 学习
        + [ ] [JupyterHub]()
    + 游戏
        + [ ] [语音服务器 - TeamSpeak]()
        + [ ] [Minecraft - MCSM]()
    + 其他
        + [ ] [反向代理]()
            + [ ] HomeAssistant

