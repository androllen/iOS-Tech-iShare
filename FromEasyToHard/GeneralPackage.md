## xcode 打包 生成 ipa
1.打开项目 选中 项目根目录。显示程序的基本信息包括 生成 能力 资源 编译设置等  
2.找到 General 标签  
完善app定义，开发信息  
3.找到app icons and launch images 标签  
点击app icons source 右边到小箭头  
当年看到AppIcon 空白区域，右击弹出框找到  
生成LaunchImage 鼠标点中，右击 show in finder ，添加你需要的素材 此时应当掌握屏幕分辨率尺寸大小  
在LaunchImage 窗口的右边，就能看到能刚才添加完的Image，用鼠标先选中图标(有蓝色细边框)此时可拖动到相应到单元格内完成。 
在当前标签下 Launch Image Source 选择 migrate 在返回旋转LaunchImage 把多余Remove。

4.[找到Linking to a Library or Framework标签](https://developer.apple.com/library/ios/recipes/xcode_help-project_editor/Articles/AddingaLibrarytoaTarget.html)可以增加第三方静态库  
