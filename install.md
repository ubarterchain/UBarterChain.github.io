---
layout: page
title: 安装调试
permalink: /install/
---
---

&#160;&#160;&#160; [首页](https://ubarterchain.github.io/) &#160;&#160;&#160; [互换信息](/info/) &#160;&#160;&#160; [物品介绍](/list/) &#160;&#160;&#160;  [安装调试](/install/) &#160;&#160;&#160;  [了解使用](/learn/) 

---
---

# &#160;&#160;&#160; &#160;&#160;&#160; 安装调试 #

---
---

### 安装互换君市场节点终端: &#160;&#160;&#160; &#160;&#160;&#160;&#160;&#160;&#160; &#160;&#160;&#160; [(参考视频)](https://www.youtube.com/watch?v=XxMdz7082yo&t=16s) ###

1. 下载Easychain.zip在 [这里](https://github.com/ubarterchain/UBarterChain3/blob/master/Easychain.zip)
2. 解压缩Easychain.zip，将其内Easychain文件夹取出放到电脑桌面。
3. 打开Easychain文件夹，点击run-easycoin。GUI就开始运行了。

注意：
运行节点客户端后，若长时间无法实现数据同步，请参考下述同步 互换君市场的数据。

---

### 同步互换君市场数据: &#160;&#160;&#160; &#160;&#160;&#160;&#160;&#160;&#160; &#160;&#160;&#160; [(参考视频)](https://www.youtube.com/watch?v=XxMdz7082yo&t=16s) ### 

为了加快节点客户端数据的同步，可以用解压缩的含有预先下载的部分区块的Easycoin文件替代现有的Easycoin。方法如下：
1. 下载Easycoin在 [这里](https://github.com/ubarterchain/UBarterChain3/blob/master/Easycoin.zip)
2. 将其解压缩后放在目录地址C:\Users\xxxx\AppData\Roaming, 其中xxxx部分会是你的电脑名字。

或者，通过查找节点客户端的调试文件（debug file)来找到该数据的存放目录地址。方法如下：
在调试文件中找到含有“CDBEnv::Open:”的哪一行，该段文字后的部分就是数据存放的目录地址。例如下列LogDir=C:\Users\yongr\AppData\Roaming\Easycoin\wallets\database其中的C:\Users\yongr\AppData\Roaming\部分。

---
---

&#160;&#160;&#160; [首页](https://ubarterchain.github.io/) &#160;&#160;&#160; [互换信息](/info/) &#160;&#160;&#160; [物品介绍](/list/) &#160;&#160;&#160;  [安装调试](/install/) &#160;&#160;&#160;  [了解使用](/learn/) 
