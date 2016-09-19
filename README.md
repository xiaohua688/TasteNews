TasteNews
--------

MVP架构的news，前期借鉴了SimpleNews的代码，后期进行了相应的完善。
SimpleNews的github地址：https://github.com/liuling07/SimpleNews


应用截图
---

![image](https://github.com/SomeOneIntheWorld/TasteNews/blob/master/app/src/main/java/com/example/asus/tastenews/screenshot/main.png)

![image](https://github.com/SomeOneIntheWorld/TasteNews/blob/master/app/src/main/java/com/example/asus/tastenews/screenshot/left.png)

![image](https://github.com/SomeOneIntheWorld/TasteNews/blob/master/app/src/main/java/com/example/asus/tastenews/screenshot/detail.png)

![image](https://github.com/SomeOneIntheWorld/TasteNews/blob/master/app/src/main/java/com/example/asus/tastenews/screenshot/detail_2.png)

![image](https://github.com/SomeOneIntheWorld/TasteNews/blob/master/app/src/main/java/com/example/asus/tastenews/screenshot/bottom_comment.png)

![image](https://github.com/SomeOneIntheWorld/TasteNews/blob/master/app/src/main/java/com/example/asus/tastenews/screenshot/comment_main.png)

![image](https://github.com/SomeOneIntheWorld/TasteNews/blob/master/app/src/main/java/com/example/asus/tastenews/screenshot/comment.png)

![image](https://github.com/SomeOneIntheWorld/TasteNews/blob/master/app/src/main/java/com/example/asus/tastenews/screenshot/float.png)

![image](https://github.com/SomeOneIntheWorld/TasteNews/blob/master/app/src/main/java/com/example/asus/tastenews/screenshot/voice.png)



完善的功能：
-------

- 使用悬浮窗，在退出应用后仍可以在桌面显示悬浮窗，点击悬浮窗后弹出一个显示新闻标签的酷炫窗口

- 后台暂时使用Bmob后端云

- 添加了登录注册功能，并且只需一次注册，永久登录

- 添加评论功能，实现交互，并且新闻中的评论以弹幕的形式出现，而且通过调整，不会影响到阅读新闻，更增加了一丝趣味

- 在新闻详情中添加了评论区域的入口，摆脱了传统的只在新闻下面说说自己的想法，简单而无太大营养。评论区域借鉴知乎的idea，设有评论区、问问题等功能，力求让每一条新闻都能让大家畅所欲言。

- 添加了语音控制功能，能够通过语音控制跳转到哪个页面。由于采用的是科大讯飞的接口，如果想要有持久唤起语音的功能就必须买，好贵啊啊啊啊，所以目前只是需要语音的时候点击menu中的语音选项，较为麻烦，请大家原谅。

采用的技术：
-----

- MVP架构
- OkHttp
- Rxjava
- Glide




再次感谢SimpleNews提供的MVP架构使得这个项目可拓展性非常强，耦合度也很低，才让功能扩展变得这么容易
感谢开源的一切大牛们
