# TFMonitor
TestFlight monitor脚本模块, 监控TF资格释放.

修改自 https://github.com/songyangzz/QuantumultX/ 

原理是采用Surge的定时执行任务功能.

# 修改内容

1. boxjs: 只保留了TF的配置, 其他前删掉了. 还无耻的把作者变成了自己.
2. js文件: 格式化代码, 替换了boxjs的最新代码.


# TODO
- [ ] 定时任务时间可修改


# 使用方法

1. 订阅 boxjs: 

  `https://raw.githubusercontent.com/hxhlb/TFMonitor/main/boxjs/sub.json`

2. 打开boxjs, 填写要监控的TF的appkey

3. surge安装模块

   `https://raw.githubusercontent.com/hxhlb/TFMonitor/main/surge/tfmonitor.sgmodel`

4. 欢快的使用
