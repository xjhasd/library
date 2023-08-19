## EthBookLibrary——一个基于以太坊和星际文件系统的去中心化的图书馆
### 提醒  因为ipfs公共网关不稳定，图书封面很大可能不能显示.

## 1 总览
本图书借阅平台可以实现去中心化的，分布式的，可溯源的图书借阅功能。
* >系统主页
* >最新公告
* >入馆指南
* >发布图书
* >借阅图书
* >归还图书
* >读者和发布者都可以评论这本图书，并且打分，可以重复评论打分
* >用户检索图书(在"我的图书"和"图书主页"可以进行关键词检索和类型检索)
* >在我的图书里面可以查看我发布的图书，评论过的图书，借阅过的图书，归还过的图书
* >图书排序(借阅量排序，评分排序，发布时间排序)
* >帮助中心(教程和作者联系方式)

### 1.1 系统主页
* >**系统主页**
![系统主页.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E7%B3%BB%E7%BB%9F%E4%B8%BB%E9%A1%B5.png)

### 1.2 最新公告
* >**最新公告**
![最新公告.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E6%9C%80%E6%96%B0%E5%85%AC%E5%91%8A.png)

### 1.3 入馆指南
* >**入馆指南**
![入馆指南.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E5%85%A5%E9%A6%86%E6%8C%87%E5%8D%97.png)

### 1.4 发布图书
* >**发布图书**
![发布图书.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E5%8F%91%E5%B8%83%E5%9B%BE%E4%B9%A6.png)

### 1.5 图书主页
* >**图书主页模块里展示了书籍的具体信息,点击红色“借阅”按钮即可借阅书籍**
![图书主页.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E5%9B%BE%E4%B9%A6%E4%B8%BB%E9%A1%B5.png)

* >**用户是不能借阅自己发布的书籍的**<br />
![不能借阅自己发布书籍提示图.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E4%B8%8D%E8%83%BD%E5%80%9F%E9%98%85%E8%87%AA%E5%B7%B1%E5%8F%91%E5%B8%83%E4%B9%A6%E7%B1%8D%E6%8F%90%E7%A4%BA%E5%9B%BE.png)


* >**不可以重复借阅同一本书**<br />
![同一用户不可以重复借阅同一本书提示图.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E5%90%8C%E4%B8%80%E7%94%A8%E6%88%B7%E4%B8%8D%E5%8F%AF%E4%BB%A5%E9%87%8D%E5%A4%8D%E5%80%9F%E9%98%85%E5%90%8C%E4%B8%80%E6%9C%AC%E4%B9%A6%E6%8F%90%E7%A4%BA%E5%9B%BE.png)

### 1.6 我的图书
* >**在我的图书界面里可以看到我发布的图书、我评价的图书、我借阅的图书以及我归还的图书的具体信息**
![我的图书.png]()

* >**在此模块的最上方，是可以按照关键字和类型搜索想要查询的图书。若在查询图书时输入错误的关键字则会进行提示**
![查询图书失败提示图.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E6%9F%A5%E8%AF%A2%E5%9B%BE%E4%B9%A6%E5%A4%B1%E8%B4%A5%E6%8F%90%E7%A4%BA%E5%9B%BE.png)

* >**在“我的图书”下面的借阅的图书里面是可以归还图书的，已经归还了的图书是不用归还的**<br />
![归还图书.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E5%BD%92%E8%BF%98%E5%9B%BE%E4%B9%A6.png)

* >**成功归还图书提示图**<br />
![成功归还图书提示图.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E6%88%90%E5%8A%9F%E5%BD%92%E8%BF%98%E5%9B%BE%E4%B9%A6%E6%8F%90%E7%A4%BA%E5%9B%BE.png)

* >**归还图书失败提示图**<br />
![归还图书失败提示图.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E5%BD%92%E8%BF%98%E5%9B%BE%E4%B9%A6%E5%A4%B1%E8%B4%A5%E6%8F%90%E7%A4%BA%E5%9B%BE.png)

### 1.7 评论图书
* >**可以多次评论图书**
![评论图书.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E8%AF%84%E8%AE%BA%E5%9B%BE%E4%B9%A6.png)

* >**发布者和普通用户的评论有所区分（发布者的评论头像为红色，普通用户的评论头像为绿色）**
![网友评价.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E7%BD%91%E5%8F%8B%E8%AF%84%E4%BB%B7.png)

### 1.8 图书排行
* >**图书排行支持借阅量排行、评分排行(默认支持的是评分排行)、图书发布时间排行**
* >**借阅榜**
![借阅榜.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E5%80%9F%E9%98%85%E6%A6%9C.png)
* >**时间榜**
![时间榜.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E6%97%B6%E9%97%B4%E6%A6%9C.png)
* >**评分榜**
![评分榜.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E8%AF%84%E5%88%86%E6%A6%9C.png)

### 1.9 帮助中心
* >**相关介绍和作者联系方式**
![帮助中心.png](https://github.com/ljxlzr/library-photo1/blob/main/docs/%E5%B8%AE%E5%8A%A9%E4%B8%AD%E5%BF%83.png)


## 2 运行前准备

<a name="8e98bd52"></a>
## 2.1 安装IPFS
* 下载ipfs压缩包

$ wget https://dist.ipfs.tech/kubo/v0.18.1/kubo_v0.18.1_linux-amd64.tar.gz
* 解压

tar -xvzf kubo_v0.18.1_linux-amd64.tar.gz
* 移动文件

$cd go-ipfs<br />$ sudo mv ipfs /usr/local/bin/ipfs
* 在本地计算机建立一个IPFS节点

ipfs init
* 跨域资源共享CORS配置

$ipfs config --json API.HTTPHeaders.Access-Control-Allow-Methods '["PUT", "GET", "POST", "OPTIONS"]'<br />$ ipfs config --json API.HTTPHeaders.Access-Control-Allow-Origin '["*"]'<br />
* 启动ipfs服务

$ ipfs daemon

* 浏览器访问IPFS节点

http://localhost:5001/webui
* [IPFS公共网关](https://ipfs.github.io/public-gateway-checker/)


<a name="f15fc2c3"></a>
## 2.2 安装truffle框架
* sudo apt-get install nodejs
* sudo apt-get install npm
* sudo npm install -g truffle
* 安装指定版本的truffle——sudo npm install -g truffle@"指定版本"

例子：sudo  npm install -g truffle@5.0.0


<a name="b9063e78"></a>
## 2.3 安装[ganache](https://truffleframework.com/ganache)测试框架
* 在官网（https://trufflesuite.com/ganache/）下载适合主机版本的ganache
<a name="1dfd2bcd"></a>
## 2.4 安装以太坊浏览器插件[metamask](https://chrome.google.com/webstore/category/extensions)

* 在谷歌应用商店里下载安装插件metamask，将其添加至chrome，依次输入账户名和密码创建钱包并确认自己账户的助记词

* metamask关联truffle框架

打开metamask——>设置——>显示助记词——>复制助记词

打开ganache——>设置——>ACCOUNTS&KEYS——>输入助记词，完成关联<br />

<a name="d0617cd1"></a>
## 3 项目目录
* build

智能合约编译后生成的json文件
* contracts

智能合约
* migrations

智能合约部署脚本
* src（项目应用层和中间层）
* test

智能合约测试脚本

<a name="733d6c7b"></a>
## 4 项目运行
* 启动IPFS

ipfs daemon
* 启动ganache

./ganache<br />windows就直接双击ganahce.exe即可。
* 编译

truffle compile
* 部署

truffle migrate
* 安装项目依赖(第一次运行项目)

npm install
* 运行

npm run dev<br />会自动打开浏览器通过localhost:3000访问<br/>（若未自动的打开，可以在浏览器中输入该网址，刷新后即可）

<a name="8382c147"></a>
## 5 参考资料
* [游戏交易系统](https://github.com/littleredhat1997/Egame) **十分感谢！**
* [truffle官方教程宠物商店](https://truffleframework.com/tutorials/pet-shop)

---
有问题可以提issues，欢迎star、~
---



