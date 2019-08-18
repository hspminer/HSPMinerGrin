![](/logo.png)

# HSPMiner

用于显卡GPU的`Grin`挖矿软件。

## 下载地址

[从这里下载](https://github.com/hspminer/HSPMinerGrin/releases)

## 社区支持

官方QQ群： 870349675

## 参考算力（默认频率）

| Algorithm        |  Coin   | P106-100  |  P104-8G   |  1070ti  |  1080ti  |   2080   |
| :--------------- | :-----: | :-------: | :--------: | :------: | :------: | :------: |
| cuckaroo         | GRIN29  |   3.45    |    5.6     |   5.25   |   8.1    |   ...    |
| cuckarood        | GRIN29  |   3.45    |    5.6     |   5.25   |   8.1    |   ...    |


## 功能特点

- 支持Windows和Linux
- 支持备用矿池的设置
- 支持SSL方式连接矿池
- 开发手续费:
  - 


## 配置需求

- **NVIDIA显卡驱动版本，大于等于377**
- 显卡参数需求:

|    Algorithm     |  Coin   | Compute Capability | Memory (Win7 & Linux) | Memory (Win10) |
| :--------------: | :-----: | :----------------: | :-------------------: | :------------: |
|   cuckaroo(d)    | GRIN29  | 6.0, 6.1, 7.0, 7.5 |          5GB          |      6GB       |
|     cuckatoo     | GRIN31  |   ...   |   ...   |   ...   |



## 使用样例

#### Grin29

- **f2pool:** HSPMinerGrin.exe -pool grin29.f2pool.com:13654 -wal {替换钱包地址} -worker {替换旷工名称} -psw {替换密码} -logfile -api 0.0.0.0:16666
- **sparkpool:** HSPMinerGrin.exe -pool grin.sparkpool.com:6666 -wal {替换钱包地址} -worker {替换旷工名称} -logfile -api 0.0.0.0:16666

## 命令行参数

## API查询接口

### 网页监控

在浏览器中打开 http://api_host:port/ 启动网页监控.


## FAQ


#### 为什么我的矿池算力比本地算力低?

- `矿池的显示算力`


## 修改记录

#### HSPMinerGrin 2.3.1 2019/8/17

- Add:支持C29D算法
- Add:增加对39x,41x,42x驱动支持
- 提示:有可能不支持老驱动，请使用431.60驱动


#### HSPMinerGrin 2.0.1 2019/1/16

- Add:添加对鱼池的支持
- Add:提升性能4%-5%
- Fix:修正一些bug


#### HSPMinerGrin 2.0.0 2019/1/15

- Add:实验性支持Grin C29算法

