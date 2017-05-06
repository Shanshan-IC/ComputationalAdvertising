实时竞价 Real time bidding\(RTB\)

* RTB 的流程可以分为cookie mapping 和Ad call两个过程
* cookie mapping的作用是沟通Adx和DSP，使得两边都了解有哪些cookie
* ad call是正式的广告投放

这里面有一些潜在的风险，如有些公司加入RTB目标就是用非常廉价的方式拿到用户数据，而非投广告。并且，由于多了一次访问请求返回，会增加浏览者的网页响应时间。对于用户来说，等待大约多了 100ms，这样对用户 ctr 是有影响的，并且增加了Demand端的成本和server的成本。

知乎上有一张图描述得比较完整：

![](/assets/8a9847344d0bc6afbb5b9ddefdba6c18_r.jpg)





