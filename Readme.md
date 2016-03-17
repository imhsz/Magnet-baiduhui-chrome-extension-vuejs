## BaiduHui Chrome Extension(Not Official)
---
Maintainer: [Daniel Zhu](https://github.com/DanielZhu)

> A simple extension for Google Chrome allows the user to use BaiduHui Services in the current window to this extension.

### Previews（预览）:
---

![pic_promo](https://lh3.googleusercontent.com/m5l1PeOIv39hH8jorc5WQmWdqVBc5Q2lnfu92uMfxWRSqd2r8nMdFdlyP8GB2SISOUq7Jx3OSXM=s1280-h800-e365-rw)

#### 首页
![pic_list](https://lh3.googleusercontent.com/bAJoKjuVesTl7SwaQL8KwMM_28oCPh3H71JxkCsv2G9NgX9-_jdsrzrWcEfHaXuzP60u1fFv=s1280-h800-e365-rw)

#### 详情页
![pic_detail](https://lh3.googleusercontent.com/wfeCYyyek9vuWsXJOZUbmx8dkNMv7U_WBZxWzSvXo8coqLbB2uEM0BxS1SYIgKgGTARgxulOyQ=s1280-h800-e365-rw)

#### 设置页
![pic_setting](https://lh3.googleusercontent.com/-LM42dvYFXLbOCvUT4FHy50ldVEtLrzBScxrMFAo7NWHHrLejM57M2qa5cubcqY-a_U-iftjXw=s1280-h800-e365-rw)

### Installing（安装）
---
####From official approach（从官方商店）
Go to [BaiduHui @Chrome Store](https://chrome.google.com/webstore/detail/blcmlhpbpimcnifnkgkfjhhmoolbidik) to install it directly.

#### From the source code here（从源代码）
1. Clone or download the src
2. Locate to the extesion setting page in Chrome
3. Enable the *developer mode*
4. Hit *Load unpacked extension... *
5. You got the latest extension

### Features / Description（功能与描述）
---
百度惠是百度旗下消费导购平台。我们致力于以客观中立的态度，为您推荐最具品质和性价比的消费信息。

如今，网购日益成为大家生活中不可缺少的一部分。但是，对于普通消费者来说，一面是促销手段层出不穷的商家，一面是品种繁多浩如烟海的商品，如何能够在网购过程中规避风险、选择靠谱的商家、买到最具性价比的产品，需要花费大量的时间去做功课和比价。即使如此，效率仍然相对有限。

而百度惠要做的事，就是帮助大家规避网购风险，降低网购成本。

在这里，您不但能真正在购物中省钱，体验到“一样的人民币，不一样的购买力”，还能掌握到最一针见血的纯干货消费知识，买得明白，买得超值。

本插件为非官方『百度惠』谷歌浏览器插件，包含推送功能，欢迎使用。

### v1.0.2 / 2016.03.17

**新功能**

- 首页，列表加载失败后，加入重试按钮

**优化**

- 加入对外链跳转的统计
- Logo角标数字更正为优惠项增量数
- 缓存为空时的新增量优惠项目不作推送
- 插件安装后，后台将立即请求10条数据缓存

**Bug Fix**

- 首页，加载更多项目失败时，页码还在往上累加的错误
- 首页，翻页后，缓存被旧数据覆盖的问题（由v1.0.1改动引起）
- 设置，推送频率修改后没有立即生效的问题
- 推送项目后的点击跳转问题

### v1.0.1 / 2016.03.15

**Bug Fix**

- 推送特卖活动时，修复了显示多余HTML标记文本的问题
- 在页面上修改推送开关后，实时停止推送
- 支持优惠详细介绍中的百度VIP外链跳转（保障你的返利权利）
- 修复推送时，因消息排序导致的推送内容错误问题

**优化**

- 部分界面显示问题
- 单条手动推送入口增加显示门槛

### v1.0.0 / 2016.03.13

- 支持百度惠首页精选频道商品浏览
- 支持查看精选商品和活动详情
- 支持查看详情页内评论
- 插件支持页面内设置
- 支持实时推送与音效（可定制）
- 永久缓存一页最新的优惠列表（可定制）

### Thanks To(致谢)
---
[BaiduHui](http://hui.baidu.com)


### License
---
All the data is copyright to BaiduHui Team & Baidu CO., Ltd.
MIT @Staydan.com
