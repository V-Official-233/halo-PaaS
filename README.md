# halo-PaaS

将 halo-2.x 博客部署在 raliway、Render、Replit等 平台


## 鸣谢
[Halo [ˈheɪloʊ]](https://github.com/halo-dev/halo)

## 如何使用？：

新建一个 bash 项目，在控制台中输入以下代码后回车。Replit 最好是使用教育团队！

```
curl -fsSL "https://raw.githubusercontent.com/V-Official-233/halo-PaaS/main/install.sh" | bash -s install
```


## 您需要添加以下环境变量

```
"HALO_WORK_DIR" = "${PWD}/.halo2"
"halo.external-url"="你的replit生成链接或绑定的自己的域名"
```

更多变量请参考：
[halo官方文档](https://docs.halo.run/getting-started/install/docker-compose/#%E6%9B%B4%E6%96%B0%E5%AE%B9%E5%99%A8%E7%BB%84)
