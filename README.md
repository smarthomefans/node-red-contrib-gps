# node-red-contrib-gps

汽车在线节点


## 安装

**Requires Node.js v6.0 or newer**

Either install from the Node-RED palette manager, or:

```
$ npm i node-red-contrib-gps
```

## 使用

* **gpsoo-login** 用于登陆汽车在线，目前`access_token`有效期为2小时，所以要定时获取 
* **gpsoo-monitor** 用于获取设备信息，默认`msg.payload.data`是第一个设备信息，详细设备可以从`msg.payload.dataArray`获取
* **gpsoo-address** 通过经纬度反向获取地址信息，输入参数经纬度


## QQ群 776817275 欢迎大家加入

![](https://i.loli.net/2018/12/28/5c25b8bf1e78d.jpg)

## Maintainers

[@yaming116](https://github.com/yaming116)

## License

MIT © 2018 yaming116

