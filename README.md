SqliteDemo
==========

using FMDB to query the sqlite database.



iphone开发十几个实用demo合集   

公司接了个培训项目，给一个外包公司培训一批应届生，我从课程一半开始接手，讲了一个多月，内容包括UITableView,UIScrollView,AssetsLibrary,MapKit,AddressBook,AVFoundation,MediaPlayer,Coredata,Sqlite等等。
每天晚上都会写一个demo第二天上课讲，代码里面基本都有中文注释，有的有上课用的ppt，现在把所有的例子都传到github上了。
因为每个例子都只花了我一晚上时间，有bug再所难免，大家随便看看就好
我的github主页https://github.com/yuyi012
tableview demo，使用自定义sectionHeader,能够展开和收起section，
xmpp聊天，使用xmpp加coredata实现类似微信的聊天功能。
很多人关心这个demo，特别说明一下
有两个页面，一个是气泡聊天的，ChatController
还有一个是接受的消息列表的，MessageListController
在application: didFinishLaunchingWithOpti*****中把window的rootController改成ChatController就能发消息了
还有一点需要注意的就是，xmpp聊天是需要服务器的，不过可以很简单的在电脑上安装openfire，然后在appDelegate中修改服务器的ip和域名
这个应用要看到完整的运行效果一定要开两个程序，一个模拟器，一个真机，互相发聊天
用户名和密码也是在appDelegate写死的


FMDB操纵sqlite
AssetsLibrary,使用自定义页面读取视频，照片，自定义imagePickerController一次选取多个照片。
流媒体视频播放器，长按进度条能够弹出popOverController，预览这一时间点的视频。
手势，所有的手势调用
pan手势实现的涂鸦板，线条多种颜色选择
UIScrollDemo
通知Demo，多个ViewController互相传递参数，顶部statusbar消息提醒。
弹出控件一锅烩，各种系统自带控件使用，使用UIPickerView实现二级菜单，使用动画弹出UIView并抖动，
3D翻转弹出UIView
下载Demo，分别使用NSURLConnection和ASIHttpRequest下载图片，并使用进度条和MBProgressHub提示下载进度。
MapKit Demo，在MapKit上添加自定义Annotation，显示天气情况
mapView点线面, 在地图上使用点，线，圆圈，多边形，并实现公交换乘线路的切换
联系人demo，使用AddressBook框架实现编辑群组和联系人，能够搜索联系人，实现联系人姓名拼音排序等等。
AVFoundation播放音乐，使用AVFoundation播放音乐，并提取音乐封面显示。
NSOperationDemo,,使用NSOperation后台解析100万字的txt小说，一秒就可以预览前五页，使用progressView提示解析进度
图片:iOS 模拟器屏幕快照“2012-6-2 下午3.50.49”.png 
图片:iOS 模拟器屏幕快照“2012-6-2 下午4.01.39”.png
