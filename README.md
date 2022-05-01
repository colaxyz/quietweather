# QuietWeather
一款天气应用微信小程序

## 数据来源

气象数据由 [和风天气](http://www.heweather.com/) 提供，需要注册账号获取 `key`；免费版只能获取三天的天气数据，若要获取七天的气象数据，可以申请**个人开发者认证**；

## 运行前准备
> * [注册微信小程序](https://mp.weixin.qq.com/wxopen/waregister?action=step1)，获取 `appid`，配置和风天气域名白名单(在小程序后台将使用到的 `API` 添加到域名白名单)；
> * 注册[和风天气](http://www.heweather.com/)账号，获取 'key`；
> * 在 `accountconfig.js` 中修改 `HeWeatherKey` 变量为你的和风天气的 `key`；
> * Run and Enjoy!
