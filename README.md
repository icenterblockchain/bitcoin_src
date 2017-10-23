
比特币源码研读
=================
本仓库用于提交比特币源码阅读的学员作业，形式不限，不要求强制完成。
参考资料详见这里：http://www.jianshu.com/p/2c2b0c0af659

没学过Git的请参考廖雪峰的Git教程：https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000
高级教程详见《Pro Git》第二版：https://www.gitbook.com/book/bingohuang/progit2/details
比特币源码请到这里下载：https://github.com/bitcoin/bitcoin

Git使用说明
每人新建一个自己的分支，将作业提交到自己的分支上，推送至远程服务器。
1. 下载仓库
 ```bash
 git clone https://github.com/icenterblockchain/bitcoin_src.git
 ```
 2. 新建自己的分支，分支名字为自己名字的汉语拼音
 ```bash
 git checkout -b hejianhui
 ```
 3. 提交代码或者文档
    commit信息请注明完成的是哪个问题，例如"第一次作业-比特币结构相关代码"
 提交流程
 ```bash
 git add xxx
 git commit -m "第一次作业-比特币结构相关代码"
 git push hejianhui
 ```
 
