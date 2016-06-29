>本文意见仅供参考,客观公正的对各家SDK评价

# 自己写SDK和后台:
有人评估过，iOS 3-4人团队，至少有一个熟手，安卓4-5人团队，至少一个熟手，加上后台、web等大概20人左右的团队，三个月左右搞得出来效果比较好的直播.此方案  费时费力,见效慢,项目进度不会给那么多时间,

#千聊直播
App Store 有讲师版,专门针对微信的html5 直播,appstore的版本5月底才上线,不提供SDK 服务.可以使用讲师版app 使用直播,主要用户是在微信中观看直播.无法提供SDk接入.所有的玩法都是基于微信的.目前还获取不到直播的URL,除非使用青花瓷对网页抓包,在微信里面做直播,基于微信的,很容易扩散和传播.
使用青花瓷抓包到的Url
>http://m.qlchat.com/topic/530000011022540.htm?isGuide=Y&from=singlemessage&isappinstalled=0
浏览器中打开这样的,不是我们想要的,在微信中打开这个url 是有聊天界面的,加载千聊播放界面的时候同时加载了9个以上的url,所以我们获取千聊的url 放到app中播放基本上行不通.

![屏幕快照 2016-06-29 上午11.33.49.png](http://upload-images.jianshu.io/upload_images/1194882-58cbe1019f41de49.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![屏幕快照 2016-06-29 上午11.32.26.png](http://upload-images.jianshu.io/upload_images/1194882-7339aca265e75a8f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



![屏幕快照 2016-06-28 下午5.12.51.png](http://upload-images.jianshu.io/upload_images/1194882-49ad16a7358fb675.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


#腾讯云SDK

1)视频采集源可以是电脑摄像头也可以是屏幕
2)直播结束后，软件会自动保存直播录像，需要将该录像上传到腾讯云实现点播
3)互动直播rtmp协议 ,互动直播延迟低,要互动
4)延迟30秒,有的人延迟1分钟
5)腾讯hls 协议,hls协议延迟30s-60s
6)进入后台无法开摄像头
7)提供聊天和关注等SDK



##1.界面效果
![屏幕快照 2016-06-28 下午3.37.20.png](http://upload-images.jianshu.io/upload_images/1194882-3c4b14636823cb8f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##2.技术支持
![屏幕快照 2016-06-28 下午3.39.27.png](http://upload-images.jianshu.io/upload_images/1194882-352dcd6ef3982277.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
##3.使用腾讯云的产品

![屏幕快照 2016-06-28 下午3.40.36.png](http://upload-images.jianshu.io/upload_images/1194882-1fca64e70f7541be.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![屏幕快照 2016-06-28 下午3.41.39.png](http://upload-images.jianshu.io/upload_images/1194882-df79653a96d95726.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#网易云SDK
###据说蛮不错,正在调研

[推流开发文档参考链接](http://dev.netease.im/docs?doc=iOS_LiveStreaming&) 

#阿里云直播
直接和网易合作的直播,没怎么看

#百度云直播
直播群聊中有人说是搞了个SDK 直接封装了下,直接没看,评价不好,不对此SDK评价

#保利威视直播
直播的时候可以分享,直接给URL 别人就可以播放,点播的时候需要依赖保利卫视SDK播放.分享的URL 对应的是最近一期的直播(这个分享功能不太实用 啊),专业的做视频机构.
收费比较便宜
#七牛
推流播放器据说做的比较好,一个叫女流氓的美女程序猿反馈这个还不做,分享和聊天需要自己做.
#奥点云直播
直接提供网页URl 就可以播放,没有直播分享功能.

##小道消息:
映客用的ljkplayer,也有人说自己写的,他们的大老板专门写直播的