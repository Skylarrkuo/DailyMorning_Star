# DailyMorning

2023.11.15：添加了中国的时区，解决了时区导致的天数不对的问题
2023.11.13：修复了每日金句中文&英文显示不全，但是需要更新推送模板(或许有更优雅的解决方式)
2023.08.14：修复了因为header的问题导致词霸请求无响应
2023.05.07：可以使用的新模板

```
今日：{{date.DATA}}
城市：{{city.DATA}}
天气：{{weather.DATA}}
最低气温: {{min_temperature.DATA}}
最高气温: {{max_temperature.DATA}}

🎂{{birthday1.DATA}}
🎂{{birthday2.DATA}}

今天也要多喝水哦(^▽^)

👋每日金句
☀{{note_en.DATA}}{{note_en2.DATA}}
☀{{note_ch.DATA}}{{note_ch2.DATA}}
```

2023.05.06：目前有个折中方案，大家可以自行参考，欢迎改进完成的友友提出Pull request。
一行文字不能仅使用 {{xxxx.Data}}  , {{xxxx.Data}} 前必须加可读文字。如：1. {{xxxx.Data}}