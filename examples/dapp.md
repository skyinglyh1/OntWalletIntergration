# IPFS  dApp
1. 用户A和机构A、B创建onid
2. 机构A给用户A颁发claim，并把claim原文存在ipfs返回id。机构A给用户A claim的id。
3. 用户A给机构B claim的id，机构B到ipfs查询claim

## IPFS

IPFS（InterPlanetary File System）是一个点对点的分布式超媒体分发协议，它整合了过去几年最好的分布式系统思路，为所有人提供全球统一的可寻址空间，包括Git、自证明文件系统SFS、BitTorrent和DHT，同时也被认为是最有可能取代HTTP的新一代互联网协议。

IPFS用基于内容的寻址替代传统的基于域名的寻址，用户不需要关心服务器的位置，不用考虑文件存储的名字和路径。我们将一个文件放到IPFS节点中，将会得到基于其内容计算出的唯一加密哈希值。哈希值直接反映文件的内容，哪怕只修改1比特，哈希值也会完全不同。当IPFS被请求一个文件哈希时，它会使用一个分布式哈希表找到文件所在的节点，取回文件并验证文件数据。

IPFS是通用目的的基础架构，基本没有存储上的限制。大文件会被切分成小的分块，下载的时候可以从多个服务器同时获取。IPFS的网络是不固定的、细粒度的、分布式的网络，可以很好的适应内容分发网络的要求。这样的设计可以很好的共享各类数据，包括图像、视频流、分布式数据库、整个操作系统、模块链、8英寸软盘的备份，还有静态网站。

IPFS提供了一个友好的WEB访问接口，用户可通过 http://ipfs.io/hash  获取IPFS网络中的内容，也许在不久的将来，IPFS协议将会彻底替代传统的HTTP协议

* [Ipfs repo](https://github.com/ipfs/)
* [Ipfs Js sdk](https://github.com/ipfs/js-ipfs-api)
* [Ipfs Python sdk](https://github.com/ipfs/py-ipfs-api)


## IPFS私网搭建

[私网搭建](https://github.com/lucas7788/workingdata/tree/master/ipfs)
https://github.com/lucas7788/workingdata/tree/master/ipfs/python_invoke_ipfs



 

