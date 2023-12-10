# DailyMorning

2023.11.15：添加了中国的时区，解决了时区导致的天数不对的问题<br>
2023.11.13：修复了每日金句中文&英文显示不全，但是需要更新推送模板(或许有更优雅的解决方式)<br>
2023.08.14：修复了因为header的问题导致词霸请求无响应<br>
2023.05.07：可以使用的新模板<br><br>
今日：{{date.DATA}}<br>
城市：{{city.DATA}}<br>
天气：{{weather.DATA}}<br>
最低气温: {{min_temperature.DATA}}<br>
最高气温: {{max_temperature.DATA}}<br><br>

我们已经贴贴了{{love_day.DATA}}天💝<br>
💌{{birthday1.DATA}}<br>
💌{{birthday2.DATA}}<br><br>

今天也要乖乖的多喝水哦(^▽^)<br><br>

👋每日金句<br>
☀{{note_en.DATA}}{{note_en2.DATA}}<br>
☀{{note_ch.DATA}}{{note_ch2.DATA}}<br><br>
2023.05.06：目前有个折中方案，大家可以自行参考，欢迎改进完成的友友提出Pull request。<br>
一行文字不能仅使用 {{xxxx.Data}}  , {{xxxx.Data}} 前必须加可读文字。如：1. {{xxxx.Data}}<br><br>