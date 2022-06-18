# 微信支付 API v3 Go SDK


[微信GoSDK](https://github.com/wechatpay-apiv3/wechatpay-go) 的复制版本
复制的原因是想要修改一些微信GoSDK代码,增加一些便于开发调试的功能.

## `consts.WechatPayAPIServer`

注释 [core/consts/const.go](core/consts/const.go#L10) `const WechatPayAPIServer` 

新增 [core/consts/goclub.go](core/consts/goclub.go#L3) `var WechatPayAPIServer`

这样便于开发者在本地调试时将支付接口改为本地模拟的接口地址