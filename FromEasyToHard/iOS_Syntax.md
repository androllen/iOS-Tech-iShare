1.关键词介绍  
2.函数方法  
3.属性变量 public private protect  
2.[Category](https://developer.apple.com/library/ios/documentation/General/Conceptual/DevPedia-CocoaCore/Category.html)    
5.http://my.oschina.net/mailzwj/blog/133273  
6.https://en.wikipedia.org/wiki/Objective-C  
7.https://github.com/QQVIPTeam/practice-of-ios  

@property (nonatomic, assign) 
使用assign: 对基础数据类型 （NSInteger，CGFloat）和C数据类型（int, float, double, char, 等等）
使用copy： 对NSString
使用retain： 对其他NSObject和其子类
atomic是Objc使用的一种线程保护技术，基本上来讲，是防止在写未完成的时候被另外一个线程读取，造成数据错误。而这种机制是耗费系统资源的，所以在iPhone这种小型设备上，如果没有使用多线程间的通讯编程，那么nonatomic是一个非常好的选择。
