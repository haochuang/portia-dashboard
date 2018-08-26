去年工作中需要用到爬虫，在网上找了一些开源的爬虫，但是都有各种问题，其中最接近我的需求的是Portia，但是Portia的开源版本中并没有提供dashboard，所以我花了一段时间自学前端开发技术和Python开发技术，在Portia的基础上增加了一个简单的dashboard。   
    
另外，我经常需要抓取一些需要用户登陆的网站，对于这样的网站，Portia使用了Python中的loginform模块来进行login，但是loginform是基于启发式的，它经常会猜错用户名和口令的位置，为了解决这个问题，我又模仿Selenium IDE实现了一套用户动作录制、回放的机制，也一并开源。 
    
代码可以到github上下载（https://github.com/siegfried415/portia-dashboard）,使用代码安装可能有点复杂，最简单的方法是使用docker(https://hub.docker.com/r/siegfried415/portia-dashboard)， 欢迎大家使用，并提出宝贵意见。  

-- 
通过这个项目，系统地学习了前端开发技术（Javascript、Ember.js), 后端开发技术（Python，Django），爬虫技术（scrapy），机器学习技术（scrapely），浏览器引擎（Splash，Webkit），收获很大！ 

--
验证码目前还不支持，目前最大的瓶颈还在于anti-anti-spider，我用过一些免费ip池，效果不太叫人满意，所以我考虑用p2p+区块链 的方式来搞一个“众爬”平台，如果一切顺利的话，会在今年后期的时候发布。 

参考：https://www.newsmth.net/nForum/#!article/Python/143779
