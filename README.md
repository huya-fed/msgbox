一款腾讯UED设计的提示插件
=========

> 简介：常规的页面提示方法

![](http://pic002.cnblogs.com/images/2011/277258/2011092615290679.jpg)

----------

##使用方法

	var TIPS = require('msgbox');

##api方法


####一、显示

	//图标类型 ： 1：感叹  4：成功  5：错误  6：加载中
	TIPS.msgbox.show(提示信息,图标类型);   

####二、隐藏

	TIPS.msgbox._hide();

####三、几秒后自动隐藏

	//显示时长为毫秒
	TIPS.msgbox.show(提示信息,图标类型,显示时长);




