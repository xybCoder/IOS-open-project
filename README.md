# IOS开源项目汇总

## 网络
1.[AFNetworking][1]
作者是 NSHipster 的博主, iOS 开发界的大神级人物, 毕业于卡内基·梅隆大学, 开源了许多牛逼的项目, 这个便是其中之一, AFNetworking 采用 NSURLConnection + NSOperation, 主要方便与服务端 API 进行数据交换, 操作简单, 功能强大, 现在许多人都用它取代 ASIHTTPRequest
2.[RestKit][2]
主要用于 iOS 上网络通信, 允许与 RESTful Web 服务交互, 常用于处理 API, 解析 JSON, 映射响应对象等操作, 简单易用, 方便你把所有精力都放在对数据的操作上
3.[MKNetworkKit][17]
一个轻量级网络请求框架, 完全基于 ARC, 仅有两个类, 具有自主操作多个网络请求, 更加准确的显示网络活动指标等优点

## Json库
1.[JSONKit][3]
主要用于解析 JSON, 适用于 iOS6 以下环境, 自从 iOS5 开始 Apple 官方给出了 NSJSONSerialization API, 自此大家都用官方的了


##  加载网络图片
1.[SDWebImage][4]
作者 Olivier Poitrey 是 Dailymotion 的 CTO, 拥有多个不错的开源项目, 此项目常用于对从 Web 端接受到的图片进行缓存, 是 UIImageView 的扩展, 应用起来比较简单

## 响应式编程
2.[ReactiveCocoa][5]
由 GitHub 工程师们开发的一个应用于 iOS 和 OS X 开发的函数响应式编程新框架, Matt 称其为 "An open source project that exemplifies this brave new era for Objective-C"

## 数据库
1.[FMDB][6]
一个对 SQLite 进行封装的库, 使用起来方便, 简单

## UI
1.[FlatUIKit][7]
收集了很多扁平化 UI 的 iOS 组件, 方便使用
2.[SVProgressHUD][8]
又一款轻量级的 iOS 第三方控件, 用于显示任务加载时的动画, 非常轻便, 容易使用
3.[RESideMenu][10]
作者 Roman Efimov 是雅虎的 iOS 工程师, 这个项目实现了 iOS 上的菜单侧滑效果, 创意来源于 Dribbble, 该项目支持 iOS8
4.[MMDrawerController][11]
一个轻量级, 易于使用的侧边抽屉导航 iOS 控件
5.MWPhotoBrowser[12]
一款简单的 iOS 照片浏览控件
6.[QuickDialog][13]
用于快速创建复杂的 iOS 表单, 自定义了 UITableViewCell, TableView 的样式
7.[SVPullToRefresh][14]
一款只需一行代码便可集成上拉刷新和下拉加载的组件
8.[PureLayout][15]
一个简单却强大的 AutoLayout API 库, 兼容了 Objective-C 和 Swift, 扩展了 UIView/NSView, NSArray, 和 NSLayoutConstraint


## 日志
1.[CocoaLumberjack][9]
这是 Mac 和 iOS 的一款强大的日志框架, 配置简单, 多线程, 提供更高级的 log 功能, 可用于代替默认的 NSLog 语句



## 工具
1.[MacDown][16]
Mac OS X 下的一款开源的 Markdown 编辑器, 创意来自与 Mou, 使用 brew cask 即可完成安装

[1]: https://github.com/AFNetworking/AFNetworking
[2]: https://github.com/RestKit/RestKit
[3]: https://github.com/johnezang/JSONKit
[4]: https://github.com/rs/SDWebImage
[5]: https://github.com/ReactiveCocoa/ReactiveCocoa
[6]: https://github.com/ccgus/fmdb
[7]: https://github.com/Grouper/FlatUIKit
[8]: https://github.com/SVProgressHUD/SVProgressHUD
[9]: https://github.com/CocoaLumberjack/CocoaLumberjack
[10]: https://github.com/romaonthego/RESideMenu
[11]: https://github.com/mutualmobile/MMDrawerController
[12]: https://github.com/mwaterfall/MWPhotoBrowser
[13]: https://github.com/escoz/QuickDialog
[14]: https://github.com/samvermette/SVPullToRefresh
[15]: https://github.com/PureLayout/PureLayout
[16]: https://github.com/MacDownApp/macdown
[17]: https://github.com/MugunthKumar/MKNetworkKit






