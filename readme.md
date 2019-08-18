![](/logo.png)

# HSPMiner

Nvidia GPU Miner for `Grin`mining.

## Download

[Download here](https://github.com/hspminer/HSPMinerGrin/releases)

## Community support

QQ： 870349675

## Performance (stock frequency)

| Algorithm        |  Coin   | P106-100  |  P104-8G   |  1070ti  |  1080ti  |   2080   |
| :--------------- | :-----: | :-------: | :--------: | :------: | :------: | :------: |
| cuckaroo         | GRIN29  |   3.45    |    5.6     |   5.25   |   8.1    |   ...    |
| cuckarood        | GRIN29  |   3.45    |    5.6     |   5.25   |   8.1    |   ...    |


## Features

* Support Windows & Linux.
* Support backup mining pool configuration.
* Support SSL connection to mining pools.
* Dev Fee: 
  *


## Requirements

- **NVIDIA graphics driver version, greater than or equal to 39x、41x、42x**
- GPU Specific Requirements:

|    Algorithm     |  Coin   | Compute Capability | Memory (Win7 & Linux) | Memory (Win10) |
| :--------------: | :-----: | :----------------: | :-------------------: | :------------: |
|   cuckaroo(d)    | GRIN29  | 6.0, 6.1, 7.0, 7.5 |          5GB          |      6GB       |
|     cuckatoo     | GRIN31  |   ...   |   ...   |   ...   |



## Sample Usages

#### Grin29

- **f2pool:** HSPMinerGrin.exe -pool grin29.f2pool.com:13654 -wal {Replace wallet address} -worker {Replace worker name} -psw {Replace worker password} -logfile -api 0.0.0.0:16666
- **sparkpool:** HSPMinerGrin.exe -pool grin.sparkpool.com:6666 -wal {Replace wallet address} -worker {Replace worker name} -logfile -api 0.0.0.0:16666

## CMD options：
-	-wal		The Grin Wallet Address
-	-worker	    The worker name of Bytom
-	-pool		The Grin pool address
-	-psw		The Grin mine password

##Run information:
-	-api		Enable the network monitoring address, such as: 192.168.1.2:16666, use the browser to access http://192.168.1.2:16666, monitor the mining machine operation
-	-logfile	Enable the log file, the default is to generate the file name according to the time, followed by the file name to specify the file, such as -logfile hspminer.log
-	-hide		Hide the interface immediately after starting the program, note that it will run in the background. If you open the api interface, you can click WebMonitor.cmd to start the browser monitoring (not available under Linux)

### Web Monitor

Open http://api_host:port/ in your browser to use web monitor.



## Change Log

#### HSPMinerGrin 2.3.1 2019/8/17

- Add: Support C29D algorithm
- Add: Added support for 39x, 41x, 42x drivers
- Tip: It is possible that the old driver may not be supported. Please use the 431.60 driver.


#### HSPMinerGrin 2.0.1 2019/1/16

- Add:Add support for f2pool
- Add:Improve performance by 4%-5%
- Fix:Fix some bugs


#### HSPMinerGrin 2.0.0 2019/1/15

- Add:Experimental support for the Grin C29 algorithm

