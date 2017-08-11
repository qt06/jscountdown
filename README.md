# jscountdown
a simple countdown script. js 实现的一个简单网页倒计时脚本。

### 用法

```
<script src="countdown.js"></script>
<script>
var cd = new Countdown(2018,1,1, 0,0,0,'距离2018年元旦还有', '.countdowndiv');
cd.setInterval();
</script>
```


### 说明

Countdown(year,month,day,hour,minute, second, title, selector);
* year: 年
* month: 月
* day: 日
* hour: 小时
* minute: 分钟
* second: 秒
* title: 需要显示的文本
* selector: 需要改变的页面元素的css 选择器，可选
