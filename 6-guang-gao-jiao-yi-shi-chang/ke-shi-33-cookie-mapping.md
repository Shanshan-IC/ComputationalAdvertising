![](/assets/1365217371_6435.png)

第一个例子：

DSP和adExchange 之间进行Cookie Mapping，由DSP发起，在广告主控制的网站上发起，mapping表存在DSP端，目的是为了获取DSP cookie和Adx cookie之间的对应关系。

当用户浏览含有DSP代码的网页的时候，网页向DSP提出询问请求，

DSP cookie服务确认该网页用户的cookie很久没有更新过了，就向该页面提出我需要同步你的cookie

然后该页面将相关信息提交给ad exchange,xid= adx cookie id\(这个不明白，dsp端是怎么获得的，是否xid是代表exchange的ID\)，did（demand cookie id），dck = demand cookie

adx把对应的xck= adx cookie返回给DSP端

到此为止，DSP端就把自己的cookie和ADX端的cookie对应起来了，存在DSP端的表里面。

当以后广告需求产生的时候，ADX把xck发给DSP，DSP在自己的表里查，这个人是不是我要的，是要的，我再出价购买。

第二个例子：

网站想了解访问自己网站用户的更多消息，或者用户的分类，标签等等，所以需要向dmp询问

网站自己存自己的用户cookie和dmp cookie的映射

如果网站想了解用户，就先查表，获得dmp cookie，然后向dmp发送这个用户的dmp cookie，dmp就返回这个用户标签等等

