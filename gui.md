---
layout: page
title: 安装调试
permalink: /gui/
---
---

&#160;&#160;&#160; [首页](https://ubarterchain.github.io/) &#160;&#160;&#160; [互换信息](/info/) &#160;&#160;&#160; [物品介绍](/list/) &#160;&#160;&#160;  [安装调试](/install/) &#160;&#160;&#160;  [了解使用](/learn/) 

---
---

# &#160;&#160;&#160; &#160;&#160;&#160; 安装调试 #

---
---

### 安装换易链市场节点终端: &#160;&#160;&#160; &#160;&#160;&#160;&#160;&#160;&#160; &#160;&#160;&#160; [(参考视频)](https://www.youtube.com/watch?v=XxMdz7082yo&t=16s) ###

1. 下载Easychain.zip在 [这里](https://github.com/ubarterchain/UBarterChain3/blob/master/Easychain.zip)。  (然后点击打开页面的右侧的“Download”即可自动下载）
2. 解压缩Easychain.zip，将其内Easychain文件夹取出放到电脑桌面。
3. 打开Easychain文件夹，点击run-easycoin。GUI就开始运行了。

注意：
运行节点客户端后，若长时间无法实现数据同步，请参考下述同步换易链市场的数据。

---

### 同步换易链市场数据: &#160;&#160;&#160; &#160;&#160;&#160;&#160;&#160;&#160; &#160;&#160;&#160; [(参考视频)](https://www.youtube.com/watch?v=XxMdz7082yo&t=16s) ### 

为了加快节点客户端数据的同步，可以用解压缩的含有预先下载的部分区块的Easycoin文件替代现有的Easycoin。方法如下：
1. 下载Easycoin在 [这里](https://github.com/ubarterchain/UBarterChain3/blob/master/Easycoin.zip)
2. 将其解压缩后放在目录地址C:\Users\xxxx\AppData\Roaming取代已有的Easycoin文件, 目录地址中xxxx部分应该是你的电脑名字，例如yongr。

或者，通过查找节点客户端的调试文件（debug file)来找到该数据的存放目录地址。方法如下：
在调试文件中找到含有“Default data directory”的哪一行，该段文字后的部分就是数据存放的目录地址。例如下列Default data directory C:\Users\yongr\AppData\Roaming\Easycoin其中的C:\Users\yongr\AppData\Roaming\部分就是Easycoin将要存放的目录。
<div class='fig figcenter fighighlight'>
  <img src='/01.png'>
</div>

---
---

&#160;&#160;&#160; [首页](https://ubarterchain.github.io/) &#160;&#160;&#160; [互换信息](/info/) &#160;&#160;&#160; [物品介绍](/list/) &#160;&#160;&#160;  [安装调试](/install/) &#160;&#160;&#160;  [了解使用](/learn/) 
