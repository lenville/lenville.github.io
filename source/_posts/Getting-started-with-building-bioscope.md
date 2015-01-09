title: Getting started with building bioscope
date: 2015-01-09 21:36:36
categories:
- Bioscope
tags:
- Bioscope
- Go
- Docker
---
这个项目缘起于我在工作中遇到的苦恼.
这个项目得到了朋友 [@AlphaLi](http://about.me/alphali) 的鼎立支持, 他也是我的室友兼同事, 虽然不在同组.

我之前从事的主要工作是, 绘制 [股票行情图](http://stockhtm.finance.qq.com/hqing/zhishu/000001.htm), 在实现的过程中, 我需要大量的实时数据的支持, 问题是, 并没有哪一台服务器支持我们在非交易时间模拟实时数据, 这令我感到非常苦恼, 于是我想到这样一个好玩儿的项目, 在外部模拟一个股价记录机, 随时记录波动的股价, 在需要的时候再像放映机一样播映出来

基于这样一个简单的创想, 我们准备使用 Golang 以及 Docker 来辅助我们进行一系列的开发.
这一系列的文章会持续记录我们使用到的资料, 取得的进展 以及 获得的经验.

这个项目的地址是 [@Github](https://github.com/lenville/bioscope),如果您有任何更好的意见或建议欢迎 [向我们提出](https://github.com/lenville/bioscope/issues)
