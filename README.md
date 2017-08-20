# Deploy code to server
1. npm run deploy
2. 登录 [DaoCloud](https://dashboard.daocloud.io/packages/354b1387-c8eb-4589-a5c5-05a045c05c10)
3. 找到 letsgo-deploy 项目, 查看版本，选择镜像，选择版本，把最近的设置为latest
4. 登录 [Rancher](http://rancher.cloudwarehub.com:8080/env/1a5/apps/stacks/1st39)
5. 找到letsgo-deploy 项目，点击右边的upgrade, 默认配置就行
