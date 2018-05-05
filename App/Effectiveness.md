目标客户：
目标用户：企业员工


# 决策管理 #

## 1、确定问题的性质 ##

经常性问题，这是我第一次遇到，而对于别人来说是一件经常发生的事情

## 2、边界条件 ##

- 用户管理： 不需要用户注册
- 群体任务信息共享：可以共享工作计划
- 任务管理：添加任务、查看当天的任务列表（已经完成和未完成）、查看所有任务列表、根据重要性、紧急程度分成4个等级、有完成标识。
- 时间管理：添加时间管理、备忘功能、统计
- 次数管理：手淫的次数、想念一个人的次数、频率，统计一周内，一个月内，一年内
- 德鲁克思想：
- 用户管理：个人的分类（任务分类、个人时间分类、不同频次的事情分类）
- 速度要比较快，使用redis



## 3、制定方案 ##

- 服务器：网站域名申请、备案、云服务器
- 小程序：分页面
- 数据库：表设计

用户的个人分类：任务分类、时间占用分类、

### 3.1、服务器 ###

- 云服务器申请：完成
- 域名申请：完成
- 域名备案：进行中。。。
- 安装MySQL数据库

### 3.2 搭建线下服务器 ###

- mysql数据库
- linux服务器（服务器版本）
- Gitj 
- jenkins
- redis
- rocket mq
- codesmith
- maven


### 3.3、用户管理 ###

用户数据表字段：

- ID bigint 是要用自增Id，还是要用snowflake算法呢
- uid varchar 128 
- wxopenid varchar 128 对应微信用户的openid
- uname varchar 20 用户微信名或真实姓名
- ugender int 0 用户性别
- uavatar varchar 128 用户头像
- skey 用户登录态标识
- sessionkey 微信登录态标识
- create_time 创建时间
- update_time 更新时间
- is_valid 是否有效

思路：

1、确认是否可以获得用户的信息
2、如果可以获得信息


### 3.4、任务管理 ###

所需要的字段：

- 任务名称
- 开始时间
- 结束时间
- 创建时间
- 更新时间

## 4、可实施的行动 ##

## 4.1、安装Linux Centos6.8 ##

## 4.2、安装MySQL ##

## 4.3、搭建微服务的架构 ##

有那个网站的项目，不在意于一时，要一下子看完。

我的直播项目

我购买的视频：腾讯图灵学院

微信端搞清楚，如何获得用户信息，都需要哪些字段

jenkins使用
redis安装

## 4.4、微信用户表的设计 ##

服务端：我看一下xiangzepro的微信的文章，是怎么写的； https://www.imooc.com/t/4264265

把这几个类抄写下来，
snowfalke算法也写下来

客户端：看一下ikcamp的发送请求是怎么做的，工具如何封装的

客户端：微信的官方文档

设计表的字段

codesmith

## 4.5、微信用户表的设计 ##

- wx.login()
- wx.request()
- wx.getUserInfo()

如何部署到tomcat上？

服务器端httpclient

## 4.6 用户注册/登录流程 ##

查看wxcode--> wx_openid --> 检查数据库是否存在：如果没有，则注册；如果有，则返回




## 5、反馈 ##

前提：管理价值观念，工具只是辅助手段。

目的：

我们推行的不是工具，而是价值观：如何让自己卓有成效。
德鲁克管理思想、乔布斯death演讲

目标：定位于职场当中，更加职场目标专注于公司的贡献，规划自己的任务、时间安排，投入自己的精力，有高的产出。

个人、部门、公司、设置

可以看到所有人的计划。

一定要体现合作的因素在里面。



如何加入公司某个部门

任务管理

时间管理

计划随时间变化的进度

小程序的权限，应该放到像过滤器的地方去做。

我用MQ来实现数据库与Redis的同步











# 微信开发中的URL #

## API文档 ##

[微信小程序文档](https://developers.weixin.qq.com/miniprogram/dev/) 

## 完整课程 ##

[9小时搞定微信小程序开发](https://github.com/SuperJolly/wxapp-tutorial-api)和[源码](https://github.com/SuperJolly/wxapp-tutorial-api)

[SpringBoot+MyBatis搭建迷你小程序](https://www.imooc.com/learn/945) 和 [源码](https://gitee.com/xiangze/)

## 示例教程 ##

[微信小程序四（设置底部导航）](https://blog.csdn.net/wujiangwei567/article/details/52763344)

## 示例项目 ##

[任务清单,dailytask](https://github.com/techidea8/dailytask)

[Tencent/weui-wxss](https://github.com/Tencent/weui-wxss)

[springboot-weapp-demo](https://github.com/nosqlcoco/springboot-weapp-demo)

## 辅助工具 ##

[Java下利用Jackson进行JSON解析和序列化](https://blog.csdn.net/zmx729618/article/details/52161069)

[Pretty Print JSON output using Jackson](https://stackoverflow.com/questions/14515994/convert-json-string-to-pretty-print-json-output-using-jackson)

[微信小程序之用户数据解密(七)](https://www.cnblogs.com/nosqlcoco/p/6105749.html)

[微信小程序开发(一) 微信登录流程](https://blog.csdn.net/sk719887916/article/details/53761107)

[微信小程序登录逻辑整理](https://blog.csdn.net/hss01248/article/details/53405251)

[小程序 侧滑删除（左滑删除）](https://blog.csdn.net/u011072139/article/details/54692237)

## 文化 ##

[Know thyself, Nothing in excess](https://www.zhihu.com/question/19774352)

## 图标 ##

[阿里通信图标库](http://www.iconfont.cn/collections/detail?cid=29)

















# 名词解释 #

## 登录 ##

Log in、Log on、Sign in都是登录的意思
Log out、Sign out是退出

Sign up是注册（"up"是向上的意思，就是向服务器提交信息）

区别在于相邻位置上注册和登录的按钮尽量用不同字母开头的词，方便用户快速辨识。如：Log in / Sign up就比Sign in / Sign up要好。



















# 编程过程中的笔记 #

## 变量cb ##

变量：

cb == call back function

## 功能：延时执行 ##

微信小程序 延时执行 定时执行

```javascript
setTimeout(function () {  
     //要延时执行的代码  
    }, 1000) //延迟时间 这里是1秒  
```

## 功能：赋值Object.assign() ##

`Object.assign()` 方法用于将所有可枚举属性的值从一个或多个源对象复制到目标对象。它将返回目标对象。[Object.assign()](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)

```javascript
const object1 = {
  a: 1,
  b: 2,
  c: 3
};

const object2 = Object.assign({c: 4, d: 5}, object1);

console.log(object2.c, object2.d);
// expected output: 3 5
```

## 功能：JSON格式化对象数据 ##

JSON.stringify(res)











# weixin API #

## wx.canIUse ##

[wx.canIUse](https://developers.weixin.qq.com/miniprogram/dev/api/api-caniuse.html)：位于“设备-->系统信息”

示例：`wx.canIUse('button.open-type.getUserInfo')`，里面的值可以在“组件-->表单组件-->button”下的open-type中找到。























# 德鲁克管理思想 #


德鲁克：时间、事情（重要）、精力、扫除力

【时间】感受一下，一生时间在手中流逝，我用了多少时间去实现人生的理想，为何不让时间更加有效，让人生更加丰富多。回想我最近一个月的工作和生活，列出用于完成各种任务的时间。大段的时间，是非常宝贵的，是处理事情的最佳时间；假如自己当上了管理者，也不要随便打断别人的大段时间，不要随便打断别人的计划。

【时间】德鲁克管理时间：（1）了解自己的时间用在了什么地方（记录时间）；（2）管理时间，减少非生产性工作所占用的时间；（3）将“可自由运用的时间”由零星而集中成大块连续性的时段。

【时间】管理者卓有成效的第一步，就是记录实际的时间使用情况。有效的管理者往往以连续三四个星期为一个时段，每天记录，一年内记录两三个时段。他们都会发现自己的时间耗用的很乱，浪费在种种无谓的小事上。经过练习，他们在时间的利用上，必有进步。但是管理时间必须持之以恒，才能避免回到浪费的状态上去。

【要事优先+精力管理】在管理者面前，摆着**许多值得去做的工作**，但管理者的时间却非常有限。未来的机会也很多，但能抓住机会的人却太少。很多管理者不能做到**集中精力**于某项工作，其主要困难在于他们确定不了哪些事情可以缓一缓，并且能把这一决定坚持到底。

【扫除力】如果一件事情，不能创建价值，那么就尽早抛弃它。无论是东西、任务、事情，还是想法。问自己：这件事，如果不做，会有什么后果？如果答案是“不会有任何影响”，那么请立即取消。


可访问资源




学习了这个教程的所有章节，写了篇博客大概总结了一下。博客地址：http://blog.csdn.net/codejas/article/details/79341919， 想要参考源码的小伙伴可以前往：https://github.com/coderjas/springboot-study，希望小伙伴能够多多支持。















