# calendar #

calendar是自动生成日历的jQuery插件


# calendar效果图 #

![calendar效果图](https://github.com/Joannamo/calendar/blob/master/images/calendar.png)


# 使用方法 #

引用css, js

<code>
	<link rel="stylesheet" type="text/css" href="calendar_ui.css" />
	<script type="text/javascript" src="jquery-1.7.2.min.js"></script>
	<script type="text/javascript" src="calendar_ui.js"></script>
</code>

<code>
	$(".wrapper").calendar({});

</code>


# 高级方法 #

点击时间，返回选择的时间

<code>
	$(".wrapper").calendar({
		dateClick:function(currentDate){return currentDate;}
	});
</code>
