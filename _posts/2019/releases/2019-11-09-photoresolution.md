---
layout: post
title: 我怎么就被一张照片出卖了
category: it
tags: [it]
excerpt: 一张照片究竟隐藏了多少信息？
---

上篇文章[《21岁日本女星惨遭猥亵，只因自拍瞳孔倒影暴露住址？》](http://www.intelyes.xyz/it/2019/11/05/photoleak.html)发出去之后，发现大家对这个事情比较感兴趣，决定再和大家多聊聊这个领域。

还有读者朋友们给我说，为什么我拿到的图片没有找到 GPS 信息，或者我找到了图片中的 GPS 信息之后，并不知道如何在地图中找到对应的地址。

另外，除过上文[《21岁日本女星惨遭猥亵，只因自拍瞳孔倒影暴露住址？》](http://www.intelyes.xyz/it/2019/11/05/photoleak.html)的几种泄露方式外，其实还有很多其它方式也会泄露拍照人的地址信息，这篇文章继续给大家介绍。

## 1.拿到照片中的GPS信息

以我在东莞参观时用手机拍摄的照片为例，为大家进行讲解。这是一张东莞某企业内部园区的一张照片，照片中有三个黑天鹅在游泳，仅仅只看照片你很难发现它在哪里。

![](http://favorites.ren/assets/images/2019/it/photoresolution01.jpeg)

如果我把这张照片以**原图**分享到社交网站上面，就有人可以通过照片的相关信息，找到我拍摄这张照片的时间、地点以及其它属性。
拿到这张照片之后，在 PC 上操作“右键-属性-详细信息”，就可以看到这张照片的很多内容，比如我就可以从这张照片中提取出以下信息：

- 照片使用的手机是：Mi Note 3
- 照片的拍摄时间是：2019/3/5 10:21:23 分（注意：这个时间是当地时间)
- 拍照地点的纬度是：22；52；52.07060000000638
- 拍照地点的经度是：113；53；1.3338000000221939

**需要强调的是只有原图才有 GPS 等相关信息，现在很多软件默认会压缩图片抹去相关信息。**

## 2.通过GPS信息定位

这照片中最关键的信息其实就是 GPS 相关信息，因为我们需要通过 GPS 来定位拍摄人的地点。

![](http://favorites.ren/assets/images/2019/it/photoresolution02.jpeg)

当然这个地址是不能直接用的，需要做一点转化，这也是很多读者说自己拿到GPS信息后，却不知道如何查询拍摄地址的原因。
有了这个GPS还不够，还得转换一次。网上**纬度经度转换**转化工具很多，比如说这个在这个网站《经纬度格式转换工具》。

![](http://favorites.ren/assets/images/2019/it/photoresolution03.jpeg)

纬度和经度都转换后，保存好两长串数字，例如我上面转化后的数字 22.881130722222224,113.88370383333334，中间用英文的逗号隔开，下面我们就可以通过这个数字来查询地址了。

在谷歌地图中搜索地址 22.881130722222224,113.88370383333334，就可以找到照片的拍摄地点了，缩小一下就可以看出这里是华为东莞松山湖园区。

![](http://favorites.ren/assets/images/2019/it/photoresolution04.jpeg)

当然这种方式比较麻烦了，有人帮大家开发了现成的工具，只需要上传照片即可获取到照片中的相关信息，并且用地图展示出照片的地址，避免人工多次转化定位。（公号内回复：**地址**，即可获取）

## 3.图片中的关键信息

我们可以依赖图片中的关键信息，来定位拍摄图片的位置。
比如图中有电话号码，无论是手机号还是固定电话，都比较容易定位到具体的城市，甚至有时可以直接定位到具体地址，比如下图照片中的背景有店铺电话信息。

![](http://favorites.ren/assets/images/2019/it/photoresolution05.jpeg)

放大之后可以看到这个电话是：075-256-6161

![](http://favorites.ren/assets/images/2019/it/photoresolution06.jpeg)

使用谷歌搜索可以检索到这家店的官网，再通过他们的官网信息可以查到，这家地址是：“京都市中京区蛸薬師通高倉西入泉正寺町334”。
这种例子还有拍摄到的人物个人信息，社交账号，被拍的人三人左右的关系网，工作单位，学校等。或者图中有商铺名称（比如周黑鸭第236号分店）或者门牌号码（忠孝东路12号），根据门牌号码和街道可以知道位置。

例如下面这张图片，图片的右侧有一个街道名称。

![](http://favorites.ren/assets/images/2019/it/photoresolution07.jpeg)

街道名称：澳门跛腳梯，那定位就十分精准了。

![](http://favorites.ren/assets/images/2019/it/photoresolution08.jpeg)

## 4.使用搜索引擎以图搜图

这是我在外旅行时拍的一张照片，从外景可以看出来应该不在国内，但具体在哪里如果不是当地人应该很难判断出来。

![](http://favorites.ren/assets/images/2019/it/photoresolution09.jpeg)

但是当我使用谷歌图片搜索，以图搜图的方式去检索的时候，搜索引擎自动可以检测出来照片的地址在时代广场。

![](http://favorites.ren/assets/images/2019/it/photoresolution10.jpeg)

百度搜索也有以图搜图的功能可以使用。

## 5.用照片中的关键建筑来定位拍摄者

我在知乎上看到了这样一个例子，可以根据建筑的位置来判定拍摄者的位置。比如我们看到了这么一张照片，没有GPS信息，那么如何定位拍摄者的地址呢？

![](http://favorites.ren/assets/images/2019/it/photoresolution11.jpeg)

首先根据照片中的建筑特点，将河岸两边的建筑标记为 A B C D E F G 。

![](http://favorites.ren/assets/images/2019/it/photoresolution12.jpeg)

使用卫星地图确定各个建筑的各个方位，并标记出 A B C D E F G 都在地图的什么位置。

![](http://favorites.ren/assets/images/2019/it/photoresolution13.jpeg)

在第一张平面图中，把他们一对一连起来画垂直线。

![](http://favorites.ren/assets/images/2019/it/photoresolution14.jpeg)

根据卫星地图中的位置，按照上面图片中垂直线把他们连接起来，尽量精确，发现上面三条线都指向了一个白色的楼房。

![](http://favorites.ren/assets/images/2019/it/photoresolution15.jpeg)

然后再放大卫星地图，就可以找到拍摄者是在哪个大楼拍摄的照片。

![](http://favorites.ren/assets/images/2019/it/photoresolution16.jpeg)

不知道大家看完这个案例什么感觉，真是世上无难事，只怕有心人，只要你愿意就可以从一张普通照片中挖掘出无限的信息，特别是即将到来的1亿像素时代。

## 6.最后

结合着上一篇[《21岁日本女星惨遭猥亵，只因自拍瞳孔倒影暴露住址？》](http://www.intelyes.xyz/it/2019/11/05/photoleak.html)文中的照片泄露地址事件，我们可以得知普通一张照片中充满了线索，如果平时不注意的话可能就会泄露隐私。

历史上也有一些因为照片泄露地址的著名事件，网络安全钢铁侠之称的 McAfee 就因为逃亡过程中，不小心因为自拍泄露地址被警方抓获，王进喜照片泄密事件、美国美军因自拍泄露军事情报等。

大家如果对这些历史事件感兴趣，可以在文章下面留言告诉我，我抽时间给大家家聊聊黑客大王是如何被照片泄露地址被警方抓获，以及王进喜照片泄密事件的真相。