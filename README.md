# Flutter_Newshub

一个基于[Flutter](https://flutter.dev/)框架实现的新闻App.
代码位于`/lib/rebuild`目录中
## 功能
- 登录注册
- 频道切换
- 下拉刷新\上拉加载(使用[easyrefresh](https://github.com/xuelongqy/flutter_easyrefresh)实现)
- 收藏\访问历史
......


## 注意
- 原App新闻数据源自[易源数据](https://market.aliyun.com/products/57126001/cmapi011150.html#sku=yuncode515000003)的API, 请自行替换AppCode
- 原App中所有的推荐功能均需配合后台的相关API实现,

## 效果图
![新闻列表](https://pic-1253509712.cos.ap-shanghai.myqcloud.com/%E6%96%B0%E9%97%BB%E5%88%97%E8%A1%A8.gif)![新闻详情](https://pic-1253509712.cos.ap-shanghai.myqcloud.com/%E6%96%B0%E9%97%BB%E8%AF%A6%E6%83%85.gif))

![注册登录](https://pic-1253509712.cos.ap-shanghai.myqcloud.com/%E6%B3%A8%E5%86%8C.gif)![新闻详情](https://pic-1253509712.cos.ap-shanghai.myqcloud.com/%E6%94%B6%E8%97%8F.gif))

![下拉推荐](https://pic-1253509712.cos.ap-shanghai.myqcloud.com/%E4%B8%AA%E6%80%A7%E5%8C%96%E6%8E%A8%E8%8D%90.gif)![相似新闻](https://pic-1253509712.cos.ap-shanghai.myqcloud.com/%E6%8C%89%E6%96%B0%E9%97%BB%E6%8E%A8%E8%8D%90.gif))


![设置页面](https://pic-1253509712.cos.ap-shanghai.myqcloud.com/%E8%AE%BE%E7%BD%AE%E9%A1%B5%E9%9D%A2.gif)


## 用到的第三方插件
插件名 | 作用 | 
-|- | 
cupertino_icons | ios图标 |
flutter_webview_plugin| App内打开url |
flutter_html | 解析HTML数据 | 
dio | 网络请求与解析 | 
fluttertoast | 弹出toast | 
flutter_easyrefresh | 下拉\上拉 | 
shared_preferences | 数据持久化 | 


