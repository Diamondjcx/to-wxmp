# to-wxmp
微信跳转小程序

# 功能
实现短信跳转小程序

# 兼容
pc端：生成二维码，可以在微信中进行扫码打开
微信端：使用 微信开放标签 “wx-open-launch-weapp”直接打开小程序
短信端：原理是访问手机浏览器打开url地址，其内部是通过“URL Scheme”进行跳转
安卓端内部是location.href进行跳转。
