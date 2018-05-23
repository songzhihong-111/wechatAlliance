# wechatAlliance 校园小情书联盟
#### 这是一个关于微信小程序-校园小情书统一中央服务器的概念

核心的理念就是：我们提供一个统一api后台服务器，微信小程序前端都用这个接口，微信小程序不需要自己部署后台，然后微信前端统一拉取同一版本的代码。校园团队负责运营和推广，平台负责提供技术服务，从而实现校园小情书的本地化。

微信小情书是一个用于大学校园情感交流互动的平台，主要功能是表白墙，卖舍友，以及暗恋。这些功能都还是很不完善，但是完善只是时间问题而已。这个小程序我开发的初衷是做一个全国大学的，用户进来之后可以选择自己的大学。

由于我之前在一些小程序社区贴出了源码，受到了很多人的关注，特别是一些在校大学生，他们找到了我的微信，联系了我。他们表达的基本是我是一个大学生，我没有编程能力，但是我希望我能部署校园小情书，只做我自己学校的。我给他们做了个小教程，但是他们还是没法完成部署。慢慢的，联系我的人越来越多，他们都想做自己学校的小情书。他们这种行为引起了我的注意，我开始思考自己这个全国版的小情书是不是一开始就是有问题的。

大学到底是一个什么地方，我自己就是一个毕业的大学生，大学是一个相对封闭的区域性很强的一个特殊环境，人们对自己学校的事情特别感兴趣，而且会毫无违和感，因为发生在校园的事情就是发生在自己身边的事情，所以我们会特别注意发生在自己学校的事情，这种地理环境也决定了大学是一个归属感很强的地方。所以我觉得我一开始就是错误的，应该只针对某个学校来开发部署校园本地版的小情书，这样推广和吸收当地的大学生用户会特别的容易，大学生们也特别喜欢玩，因为这个是我们自己学校的，很有归属感。

但是问题来了，我不可能自己去每个大学部署和推广这个小情书，我更不可能一个个的帮这些大学生们部署到自己的服务器上，那样我不吃不喝都做不来，而且我也要上班。

后来，我想到了一个解决办法，我可以搞一个中央服务器，其他的小情书可以使用我部署的api服务器，我通过小程序的app id来做数据隔离，这样就不用给他们一个个的部署后台服务器了，他们只需要拉取前端的代码，然后修改配置信息就能跑起来，我的中央服务器给他们提供接口就可以了，这真是一个完美的解决方案，校园团队不需要自己搭建服务器，这样部署起来回很快。但他们又有了一个自己的小情书。他们只需要登录自己的后台账号就能查看自己小程序的数据，管理自己的小程序。

最重要的是所有学校的小情书数据都在我们手上。

这样子做是为了什么？

1、方便小情书的校园本地化，由当地的校园团队去推广运营，效果会比外人更加容易
2、我们可以以这种方式快速的占领全国大学市场

我们怎么盈利？

中国大概有三千高校，一间高校大概两万人，也就是说中国有六千万的大学生，如果一间学校的小情书能有两千用户，那我们就有了六百万的用户量，这个用户量也是个小巨人了。有了流量我们还怕什么呢。一个两千人的小程序别人可能会看不上，但是我们有三千个两千，你要推广什么，我们这个联盟统来打这个广告，那几乎可以跟微信的朋友圈广告有得一拼了。我们三千个小程序统一接受广告业务，当然也可以自己接广告，但是如果联盟需要统一广告的时候各个小程序必须配合。最后大家流量分成，按各自的贡献来领取广告收益。

我们怎么跟校园团队分成？

为了达到推广和社会效应最大化，负责运营推广的校园团队拿七成收益，我们拿小头。

