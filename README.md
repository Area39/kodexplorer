# kodexplorer Docker版本

> https://doc.kodcloud.com/v2/#/help/vs
>
> http://static.kodcloud.com/update/download/kodexplorer4.40.zip

原版镜像源于`https://hub.docker.com/r/yangxuan8282/kodexplorer`

此为个人备份版本

首次使用，请确保本地安装好docker以及docker-compose

```
git clone https://github.com/Area39/kodexplorer.git
cd kodexplorer
docker-compose up -d
open http://localhost:8088/
```

此时会发现`kodexplorer`目录下多了一个`html`目录，后期想备份的话，直接打包`kodexplorer`目录即可。

