![](/assets/6.png)

* ad serving：ad call的产生一是用户直接产生，二是通过exchange过来。

* retrieval：根据ad call的实际情况找到符合定位情况的广告
* ranking：准则是eCPM。
* session log generation：定位要根据用户行为来决定，这个LOG就是将某用户一天的行为写成一份日志，成为算法的基础。
* log提供给data warehouse或BI，BI是数据和人的接口，根据人的需求提供差别性的查询报表。
* session log也可以做受众定向，还可以做点击率模型，进行预算，计算eCPM，供ranking使用。
* page fetcher：广告不需要全网的爬虫，只需要有广告投放的页面。会爬出有广告投放的attribution（标签）。标签为广告的retrieval服务。
* customized audience segmentation：广告比较独特的一点。很多时候媒体划分的人群等分类与广告主的分类需求差别很大，这就需要为广告主个性化的分类的服务。广告主的信息要注入到媒体当中。
* RTBD和RTBS：前者是自己实时向别人做ad call，这样自己就是一个exchange，而后者是别人向我做ad call，我根据ad call向DSP询价。

  


