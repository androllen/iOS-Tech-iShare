1.准备工作：  
macbookpro   
2.环境开发  
MacOS：10.11.5 version  
IDE：Xcode Version 7.3.1 (7D1014)  go to appstore  
3.必备软件  
QQ Wechat foxmail 终端 Chrome [TeamViewer远程](https://www.teamviewer.com/zhCN/)  
4.代码管理工具  
svn   
> [详细介绍终端使用]( http://blog.csdn.net/q199109106q/article/details/8655204)  
> [下载smartsvn](http://www.smartsvn.com/) 

git and github   

5.[在 Windows 中使用 Apple 键盘](https://support.apple.com/zh-cn/HT202676)  

6.[快捷键](http://www.cnblogs.com/langtianya/p/3888157.html)  
通用的 windows 
http://www.niubb.net/a/2015/11-25/1056862.html  

| 键盘 | 说明 |
| ------------- | ------------- | 
| shift ＋ ctrl ＋<-  | 上一页  | 
| shift ＋ ctrl ＋->  | 后一页  | 
| win＋／           | 注释  | 
| ctrl＋win＋上箭头 | 切换  | 

##Apple开发者授权
> 下载渠道  
> 破解  
> 开发者  

###下载渠道  
> 1.任何应用程序都必须经过iTunesStore下载安装  
> 2.要么直接从设备里下载  
> 3.要么从电脑中通过iTunes下载后同步到设备中    

###破解
> 1.
> 2.

###开发者授权步骤  
> 1.授权设备，将开发者授权与指定的设备绑定在一起，使得这些设备可以自由安装开发者发布的IPA。  
> 2.生成授权文件.mobileprovision，这个文件会被打包进入IPA，实现设备与授权开发帐号的绑定。  
> 3.生成证书文件.p12，这个文件也会被打包进入IPA，实现应用发行商的签名以及身份验证。  

    开发者授权系统还提供了开发（Development）和发布（Distribution）两个不同的渠道。  
    开发测试的时候需要设备的绑定而实现在设备上单独安装IPA，发布的时候则不需要绑定设备。  
    所以开发与发布需要使用不同的.mobileprovision与.cer文件。  

###发布之前
> [登陆iTunes Connect](https://itunesconnect.apple.com/)  
> [发布准备](#发布准备)  
> 需要配置项目文件    
> 需要资源文件    
> 打包ipa文件  
> 保存上传ipa文件  

### 测试之前
> [登陆iTunes Connect](https://itunesconnect.apple.com/)  
> [发布准备](#发布准备)  
> 需要手机链接iTunes 显示Device ID，获取Device ID    
> 发送给开发者并绑定到测试设备中  
> 需要配置项目文件    
> 需要资源文件    
> 打包ipa文件  
> 保存上传ipa文件  

### [打包之前](http://www.adobe.com/cn/devnet/flash/articles/ios_tutorial_3_pro_cert.html)
> 需要证书，生成开发证书和发布证书 证书之前需要开发者帐号，授权文件需要app ID  
> 生成ipa文件  

###[发布准备](http://www.adobe.com/cn/devnet/flash/articles/ios_tutorial_4_itunes.html)  
> 注册开发者帐号    
> 创建应用信息  

    登陆开发者官网
    获取开发者bundle ID 产品名
