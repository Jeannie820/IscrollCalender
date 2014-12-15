IscrollCalender
===============

基于jQuery和Iscroll的日历插件

配置项：

$.fn.calenderFun({

	'minYear' : '1950',//年最小值
	'maxYear' : '2100',//年最大值
	'dateFormat'  : 'yyyy-mm',// yyyy-mm || yyyy-mm-dd
	'callBackFun':function (data){}//返回值 data.yyyy，data.mm，data.dd
	
});
