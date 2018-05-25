# eros-plugins
eros 项目开源插件集合，由 `eros 团队`、`eros 贡献者`参与贡献与维护。

## 为什么要做插件化
1. 在 `app` 开发中，很多三方库是很大的`(amap 11MB)`，如果我们一开始集成进来，对应的 `app` 无此功能，便会造成冗余，造成安装包很大。
2. 插件如果由自己管理，没有`版本控制`的概念，很容易发生`断崖式`更新，拖慢产品迭代速度等等。
3. **eros 希望每位开发者能用上优质的插件，尽量不需要额外工作量，同时对于有能力的原生开发者，eros 非常推荐他们贡献他们沉淀的插件，这样不仅帮助他们稳定插件，提示开发的平稳性，更是能造福一些不会原生开发的开发者。**

## 使用之前
请开发者实现阅读以下文档，若开发者要开发相关插件，可以先查看插件源码，照着封装。

- [插件集成方法](https://bmfe.github.io/eros-docs/#/zh-cn/app_base_library?id=%E9%9B%86%E6%88%90%E6%96%B9%E5%BC%8F)
- [插件拓展方法](https://bmfe.github.io/eros-docs/#/zh-cn/eros_plugin)

## iOS
|插件名称|使用文档|仓库地址|
|-------|------|-------|
|微信分享 + 登录| [使用文档](https://bmfe.github.io/eros-docs/#/zh-cn/plugin_wx_share)|[github](https://github.com/bmfe/eros-plugin-android-wxshare)|
|微信支付| [使用文档](https://bmfe.github.io/eros-docs/#/zh-cn/plugin_wx_pay)|[github](https://github.com/bmfe/eros-plugin-android-wxpay)|
|个推推送| [使用文档](https://bmfe.github.io/eros-docs/#/zh-cn/plugin_getui_push)|[github](https://github.com/bmfe/eros-plugin-android-getui)|
|高德地图| [使用文档](https://bmfe.github.io/eros-docs/#/zh-cn/plugin_amap)|[github](https://github.com/bmfe/eros-plugin-android-amap)|
|手势解锁 (社区贡献)| [使用文档](https://github.com/shawn-tangsc/WeexPlugin-HMGesUnlock)|[github](https://github.com/shawn-tangsc/WeexPlugin-HMGesUnlock)|

## Android
|插件名称|使用文档|仓库地址|
|-------|------|-------|
|微信分享 + 登录| [使用文档](https://bmfe.github.io/eros-docs/#/zh-cn/plugin_wx_share)|[github](https://github.com/bmfe/eros-plugin-ios-wxshare)|
|微信支付| [使用文档](https://bmfe.github.io/eros-docs/#/zh-cn/plugin_wx_pay)|[github](https://github.com/bmfe/eros-plugin-ios-wxpay)|
|个推推送| [使用文档](https://bmfe.github.io/eros-docs/#/zh-cn/plugin_getui_push)|[github](https://github.com/bmfe/eros-plugin-ios-getui)|
|高德地图| [使用文档](https://bmfe.github.io/eros-docs/#/zh-cn/plugin_amap)|[github](https://github.com/bmfe/eros-plugin-ios-amap)|
|手势解锁 (社区贡献)|使用文档|github|
