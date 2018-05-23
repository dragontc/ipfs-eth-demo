#运行环境：

	Windows 10 专业版
	
	Nodejs v10.1.0 （下载：https://nodejs.org/dist/v10.1.0/node-v10.1.0-x64.msi）
	
	Ganache-cli （安装：npm install -g ganache-cli ）
	
	Ipfs  (下载：百度)
	

1.	安装ganache-cli,设置好环境变量

启动ganache-cli

> ganache-cli

2.	设置ipfs相关参数

ipfs config --json API.HTTPHeaders.Access-Control-Allow-Methods "[\"PUT\", \"GET\", \"POST\", \"OPTIONS\"]"

ipfs config --json API.HTTPHeaders.Access-Control-Allow-Origin "[\"*\"]"

ipfs config --json API.HTTPHeaders.Access-Control-Allow-Credentials "[\"true\"]"

ipfs config --json API.HTTPHeaders.Access-Control-Allow-Headers "[\"Authorization\"]"

ipfs config --json API.HTTPHeaders.Access-Control-Expose-Headers "[\"Location\"]"

ipfs config Addresses.API /ip4/127.0.0.1/tcp/5001

3.	首先安装ipfs，设置好环境变量

启动ipfs:

> ipfs daemon


4	进入ipfs-eth目录

	执行： > npm start
	
