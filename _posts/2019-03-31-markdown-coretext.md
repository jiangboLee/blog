---
title: iOS 文本多行省略号...显示更多按钮，利用CoreText
layout: post
image: "/assets/images/markdown.jpg"
category: blog
author: lee
description: iOS 文本多行省略号...显示更多按钮
date: '2019-03-31 21:39:18'
tag:
- iOS
---

![1.gif](https://upload-images.jianshu.io/upload_images/2868618-6de22a955a28217c.gif?imageMogr2/auto-orient/strip)
### 需求是大于2行的时候显示省略号，并且最右边是一个小箭头的icon。点击小箭头展开全部，并且icon消失。这个需求还是挺蛋疼的，icon哪里不能放，要放在省略号后面。完全不是难度级别的。没办法硬着头皮上吧。最简单的肯定找找有什么现成的第三方，YYText倒是有一个差不多的。但感觉还是有差别，再加上为了这个小需求引入这么大的库，只用了一点点，不值得。一顿搜索，发现这篇系列[CoreText 入门](https://www.jianshu.com/p/0721f40ede18)。在此基础上，根据自己需求重新修改并且删除自己不需要的。
## [Demo](https://github.com/jiangboLee/CoreText)在此！