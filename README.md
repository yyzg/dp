
## 版本信息
dp2.9.0+frida_240418

## 镜像版本要求

* dp2插件需要docker镜像版本>=2.1.9.fix1
* game密码必须为默认密码
* 需要配置环境变量SERVER_GROUP_DB=cain
* 只支持希洛克大区

## 如何使用
将本目录下的文件覆盖到/data/data/dp目录
解压后目录结构如下:
请务必删除原有的libhook.so文件！！！！！！！
```shell
dp
├── df_game_r.js
├── df_game_r.lua
├── frida
├── lib
├── libdp2.so
├── libdp2.xml
├── libGeoIP.so.1
├── libhook.so
├── lua
├── lua2
├── README.md
└── script
```
