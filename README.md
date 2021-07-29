# 整合pushplus推送的京东签到脚本

## 介绍

> 使用NobyDa “京东多合一签到脚本”为基础，魔改整合pushplus推送功能。

## 使用用法
* 添加京东cookie、pushplus的SCKEY
    - `cookie`：京东cookie
    - `push_key`：pushplus的SCKEY
* 使用 `node index.js`即可开始执行脚本
* 可以配合cron语法来定时自动化执行脚本，并收到推送提示

## 获取京东cookie

* 使用项目中的Chrome插件：`JDCookie`
* Chrome中拓展程序开启`开发者模式`；
* 点击`加载已解压的拓展程序`，选择`JDCookie`目录；
* 登录[领京豆](https://bean.m.jd.com/)；
* 点击`JDCookie`即可拷贝京东cookie

## 获取pushplus的SCKEY

* 直接搜索登录[push+](https://pushplus.hxtrip.com/index)官网
* 在`一对一推送`拷贝您的`Token`

## 参考项目
* [NobyDa/Script/JD-DailyBonus](https://github.com/NobyDa/Script/blob/master/JD-DailyBonus/JD_DailyBonus.js)
* [ruicky/jd-sign-bot](https://github.com/ruicky/jd_sign_bot)
* [jerrykuku/luci-app-jd-dailybonus](https://github.com/jerrykuku/luci-app-jd-dailybonus)
