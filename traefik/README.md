
## 1.1 部署

1. 将 env.template 拷贝为 .env 并修改其内容

```
MAIN_DOMAIN=example.com # 为一级主域名 如 example.com

ACME_ACCOUNT=admin@example.com # 用于注册acme的邮箱地址，仅用声明域名归属

ALICLOUD_ACCESS_KEY=xxxx # 阿里云AccessKey，需授权DNS操作权限，用于申请通配符证书
ALICLOUD_SECRET_KEY=xxxx
```

2. 启动容器

```
sudo docker-compose up -d
```