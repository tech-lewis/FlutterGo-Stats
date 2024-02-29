# Flutter历史和现状：
2014.10 Flutter的前身Sky在Github上开源

2015.3  2015年3月18日 出现了flutter的工具包v0.0.1

2015.9  2015/9/4还没支持iOS平台. 9月9才能开始支持iOS平台(6年前的事情)

2015.10 经过一年的开源，Sky正式改名为Flutter。在Dart开发者峰会上发布了第一个版本。

2018.02 在世界移动大会（MWC）发布首个Beta版

2018.06 在(GMTC)发布首个预览版

Version 0.8变更

```
* Change assert_bundle_package_font_test to memory file system

This is to work towards being able to run the tests without `-j1` (#21113). These tests were using the real filesystem and setting/relying on fs.currentDirectory. There was a comment about this being because the memory provider didnt' support POSIX and Windows, however that seems to have changed since (and many other asset tests already do something similar to this).

* Trim trailing whitespace

* Add a workaround for Windows path slash directions

Strictly this is correct, but the real FS can tolerate either path. The in-memory file system is more strict (see https://github.com/google/file.dart/issues/112).

* Extract a helper for writing schema files in tests

* Missed file when saving!

* Remove redundant comment

* Rename writeBasicSchema -> writeEmptySchema

* Use the file we already have to write contents

* Make comments more descriptive

* Remove another dupe of writeSchema to use the shared one

* Rename schema -> pubspec_schema

* Trim whitespace

```

```
*更改内存文件系统 Memory files system

这是为了能够在没有`-j1`（#21113）的情况下运行测试。这些测试使用的是真实的文件系统，并设置/依赖于fs。当前目录。有人评论说，这是因为内存提供程序不支持POSIX和Windows，但这似乎已经改变了（许多其他资产测试已经做了类似的事情）。
*修剪尾随空格
*为Windows路径斜线方向添加变通方法
严格来说，这是正确的，但真正的FS可以容忍任何一种路径。内存中的文件系统更严格（请参阅https://github.com/google/file.dart/issues/112).
*提取用于在测试中写入架构文件的帮助程序
*保存时丢失文件！
*删除多余的注释
*重命名writeBasicSchema->writeEmptySchema
*使用我们已经写入内容的文件
*使评论更具描述性
*删除另一个writeSchema副本以使用共享副本
*重命名模式->pubspec_模式
*去空格
```



2018.12 在Flutter Live2018上发布1.0稳定版。
变更：
全新iOS风格的widget
接入约20种Firebase服务
使用Dart 2.1，生成更小的代码和更快的速度

2019.02 在世界移动大会（MWC）发布1.2
变更：
提升框架性能和质量
视频播放、WebView、Maps等bug修复
支持Android App Bundle
基于Web的编程工具套件
支持前端开发者使用HTML和CSS语法编写应用

2019.05 在Google IO大会上发布1.7，也是目前最新版本。
变更：
支持Android X
支持32位和64位的Android App Bundle和Apk
更新小部件RangeSlider以及更复杂的排版
支持游戏控制器

# Attributor-Stats iOS

- 2019年6月22日第一个项目-韩国运动服iOS App客户端

# WWDC 2014开始关注苹果开发，学习Cocoa Touch框架和OS X10.9

- OS X Yosemite Developer Preview 8 Now Available

  September 15, 2014

- Xcode 6.1 beta 2 for OS X Yosemite is Now Available

  September 15, 2014

- iTunes Connect Developer Guide Update

  September 10, 2014We’ve updated the [iTunes Connect Developer Guide](https://web.archive.org/web/20140916023021/https://developer.apple.com/library/prerelease/ios/documentation/LanguagesUtilities/Conceptual/iTunesConnect_Guide/Chapters/About.html) to include details on creating and submitting App Bundles and App Previews, and using the new TestFlight Beta Testing app.

- ![Announcing Apple Pay](https://web.archive.org/web/20140916023021im_/https://devimages.apple.com.edgekey.net/assets/elements/icons/128x128/apple-pay.png)

  Announcing Apple Pay

  September 9, 2014Today we announced Apple Pay, an exciting new feature coming soon, which will give users an easy, secure, and private way to pay for physical goods and services in your iOS 8 app using payment information stored in their iOS device. [Learn more about Apple Pay](https://web.archive.org/web/20140916023021/https://developer.apple.com/apple-pay/).

- ![Submit Your iOS 8 Apps Today](https://web.archive.org/web/20140916023021im_/https://devimages.apple.com.edgekey.net/assets/elements/icons/128x128/ios8.png)

  Submit Your iOS 8 Apps Today

  September 9, 2014Prepare your apps for the App Store by downloading the iOS 8 and Xcode 6 GM seeds now. With these latest seeds, Swift is now final and you can submit your iOS apps written with Swift to the App Store. [Learn about iOS 8 for Developers](https://web.archive.org/web/20140916023021/https://developer.apple.com/ios8/).

- ![App Review Guidelines](https://web.archive.org/web/20140916023021im_/https://devimages.apple.com.edgekey.net/assets/elements/icons/128x128/app-review-guidelines.png)

  Updated Guidelines Now Available

  September 9, 2014Check out the latest [App Store Review Guidelines](https://web.archive.org/web/20140916023021/https://developer.apple.com/app-store/review/guidelines/) before submitting your new or updated apps for review. We review all apps against these guidelines to ensure they are reliable, perform as expected, and are free of objectionable material.

- OS X Mavericks 10.9.5 (13F31) Now Available

  September 5, 2014

- iTunes Connect Update

  September 5, 2014We’ve updated parts of iTunes Connect, including My Apps, Resources and Help, and Users and Roles. To learn about all of the changes, read the latest version of the [iTunes Connect Developer Guide](https://web.archive.org/web/20140916023021/https://developer.apple.com/library/prerelease/ios/documentation/LanguagesUtilities/Conceptual/iTunesConnect_Guide/).

  

- The Hour of Code 2014

  December 4, 2014We’re supporting the next generation of innovative developers by hosting workshops and other special events during Computer Science Education week, December 8–14. And on December 11, we’ll host the Hour of Code, a free one-hour introduction to the basics of computer programming from Code.org, at your local Apple Store. [Learn more](https://web.archive.org/web/20141207010226/http://www.apple.com/retail/code/).

- ![iAd Workbench](https://web.archive.org/web/20141207010226im_/https://devimages.apple.com.edgekey.net/assets/elements/icons/128x128/iad.png)

  Automate Your Advertising with iAd

  November 21, 2014Leverage the updated iAd Workbench API to automatically create and update ad campaigns, retrieve analytics and manage bids directly on iAd Workbench. You can now promote products in [more than 100 countries](https://web.archive.org/web/20141207010226/http://support.apple.com/en-us/HT203102) across the Americas, Europe, Asia, the Middle East, Africa, and Australia. [Learn about the iAd Workbench API](https://web.archive.org/web/20141207010226/https://developer.apple.com/iad/workbench-api/).

- OS X Server 4.0.2 Developer Preview (14S347) Now Available

  November 20, 2014

- ![iAd Workbench](https://web.archive.org/web/20141207010226im_/https://devimages.apple.com.edgekey.net/assets/elements/icons/128x128/watchkit.png)

  Get Ready for Apple Watch

  November 18, 2014Now you can start creating experiences for Apple Watch that reimagine, extend, and enhance the functionality of your iPhone apps. Learn how your existing app notifications can easily show up on Apple Watch, and how to leverage WatchKit to take your apps even further with WatchKit apps, Glances, and actionable notifications. [Learn more about WatchKit](https://web.archive.org/web/20141207010226/https://developer.apple.com/watchkit/).


New Swift Development Courses Available on iTunes U
January 27, 2015

Stanford University's iOS programming course, one of the most popular on iTunes U with over 1.2 million downloads, is now being taught using Swift. Learn how to build apps with this exciting new programming language by following Stanford's curriculum: Developing iOS 8 Apps with Swift. The first two lectures for the winter 2015 quarter are now live and additional lessons will be added as they are taught. Swift courses from other internationally recognized universities, such as Plymouth University in the UK, are also now available on iTunes U with more courses from other top educational institutions coming soon.

 64-bit and iOS 8 Requirements Start Soon
64-bit and iOS 8 Requirements Start Soon
January 19, 2015

As a reminder, beginning February 1, 2015 new iOS apps submitted to the App Store must include 64-bit support and be built with the iOS 8 SDK. To enable 64-bit in your project, we recommend using the default Xcode build setting of “Standard architectures” to build a single binary with both 32-bit and 64-bit code.

Xcode 6.2 beta 4 Now Available
January 12, 2015

 What a Way to Begin the Year
What a Way to Begin the Year
January 8, 2015

The first week of January set a new record for the App Store, with customers around the world spending nearly half a billion dollars on apps and in-app purchases. New Year’s Day marked the single biggest day ever in App Store sales history. Your incredible apps generated over $10 billion for you and your peers last year, and to date, developers have earned a cumulative $25 billion from the sale of apps and games. See the full press release.

Getting Help with App Reviews and Rejections
December 30, 2014

iTunes Connect is now available after the holiday shutdown. Please remember, if you need to appeal an app rejection or request that the review of your app be expedited, the fastest way to get help is to contact the App Review Team through the Contact Us form. To view app rejection details and ask for clarification, visit Resolution Center in iTunes Connect. We look forward to seeing the innovative new apps you'll create in 2015.

64-bit and iOS 8 Requirements for New Apps
64-bit and iOS 8 Requirements for App Updates
December 17, 2014

As we announced in October, beginning on February 1, 2015 new iOS apps submitted to the App Store must include 64-bit support and be built with the iOS 8 SDK. Beginning June 1, 2015 app updates will also need to follow the same requirements. To enable 64-bit in your project, we recommend using the default Xcode build setting of “Standard architectures” to build a single binary with both 32-bit and 64-bit code.



[Mac Apps That Use Garbage Collection Must Move to ARC](https://web.archive.org/web/20151105121017/https://developer.apple.com/news/?id=02202015a)

February 20, 2015

Beginning May 1, 2015, new Mac apps and app updates submitted to the Mac App Store may no longer use garbage collection, which was deprecated in OS X Mountain Lion. Instead, migrate your apps to Automatic Reference Counting, using the migration assistant in Xcode to help with this transition. Apps may continue to use retain/release for manual memory management. For more information, read the [Transitioning to ARC Release Notes](https://web.archive.org/web/20151105121017/https://developer.apple.com/library/ios/releasenotes/ObjectiveC/RN-TransitioningToARC/Introduction/Introduction.html).

[Force Touch APIs in OS X 10.10.3](https://web.archive.org/web/20151105121017/https://developer.apple.com/news/?id=03202015a)

March 20, 2015

The Force Touch trackpad in the all new MacBook and updated 13-inch MacBook Pro with Retina display has built-in force sensors for a new level of interactivity and control within your apps. Use Force Touch APIs, including Force click, pressure sensitivity, and accelerators, to add a new dimension to your app’s user experience. [Learn more about Force Touch](https://web.archive.org/web/20151105121017/https://developer.apple.com/osx/force-touch/).



[Submit Your WatchKit Apps Now](https://web.archive.org/web/20151105121017/https://developer.apple.com/news/?id=03312015a)

March 31, 2015

It’s time. Apple Watch will be in the hands of customers on April 24. Get your WatchKit apps ready and submit them for review now. To learn more, read [Preparing Your App Submission for Apple Watch](https://web.archive.org/web/20151105121017/https://developer.apple.com/app-store/watch/).



[The New Apple Developer Program](https://web.archive.org/web/20151105121017/https://developer.apple.com/news/?id=060815d)

June 8, 2015

Now everything you need to develop, distribute, and manage your apps on all Apple platforms has been combined into one single program, making it easier than ever to bring your creativity to over a billion customers around the world.



[OS X El Capitan Now Available](https://web.archive.org/web/20151105121017/https://developer.apple.com/news/?id=060815b)

June 8, 2015

OS X El Capitan brings Metal to Mac, giving your apps unprecedented graphics and computing power. New extensibility APIs let your Mac apps work seamlessly with Photos and Safari. [See what’s new in OS X](https://web.archive.org/web/20151105121017/https://developer.apple.com/osx/pre-release/).

[watchOS 2 Now Available](https://web.archive.org/web/20151105121017/https://developer.apple.com/news/?id=060815c)

June 8, 2015

With the new features and capabilities that watchOS 2 brings to WatchKit, your apps can integrate even more closely with Apple Watch. Take advantage of the Digital Crown, microphone, Taptic engine, and health sensors to take your Apple Watch app to the next level. [See what’s new in watchOS](https://web.archive.org/web/20151105121017/https://developer.apple.com/watchOS/pre-release/).



[iOS 9 Now Available](https://web.archive.org/web/20151105121017/https://developer.apple.com/news/?id=060815a)

June 8, 2015

iOS 9 SDK includes new APIs and services that are enabling new categories of apps and features. Multitasking and gaming APIs help enhance app functionality and create immersive games. Expanded search capabilities, and new support for CloudKit, HomeKit, HealthKit, and MapKit extend iOS to more places than ever before. [See what’s new in iOS](https://web.archive.org/web/20151105121017/https://developer.apple.com/ios/pre-release/).

[Supporting IPv6 in iOS 9](https://web.archive.org/web/20151105121017/https://developer.apple.com/news/?id=08282015a)

August 28, 2015

At WWDC 2015 we announced that iOS 9 will support IPv6-only network services. All apps submitted to the App Store must support IPv6 starting in early 2016. To make sure your app is compatible, use the networking frameworks (e.g., “NSURLSession”), avoid use of IPv4-specific APIs, and avoid hard-coded IP addresses. Before submitting your app, test for compatibility.To learn more, read [Supporting IPv6 DNS64/NAT64 Networks](https://web.archive.org/web/20151105121017/https://developer.apple.com/library/prerelease/ios/documentation/NetworkingInternetWeb/Conceptual/NetworkingOverview/UnderstandingandPreparingfortheIPv6Transition/UnderstandingandPreparingfortheIPv6Transition.html#//apple_ref/doc/uid/TP40010220-CH213-SW1)and watch [Your App and Next Generation Networks](https://web.archive.org/web/20151105121017/https://developer.apple.com/videos/wwdc/2015/?id=719).
