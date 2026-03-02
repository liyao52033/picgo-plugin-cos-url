## picgo-plugin-cos-url

A PicGo plugin for cos private resource url.

将COS的私有资源链接转成外链的PicGo插件，支持阿里云OSS、`腾讯云COS(推荐)`、七牛云Kodo，如果使用腾讯云COS，先配置参数然后选择`COS自定义上传`
![](https://cnb.xiaoying.org.cn/img/20260303005602339.png)

腾讯云COS特有功能（推荐开启防盗链）
1、可选择是否开启签名
2、浏览器访问直接下载而不是预览，可配合防盗链只有白名单可以访问
3、删除相册图片同步删除cos里的图片


<strong>注意：该插件没有充分测试网址后缀的场景，设置了网址后缀可能会导致非预期的结果发生</strong>

更多需求，欢迎PR或提ISSUE。

## 配置

过期时间设置永久：`expireSeconds=0`

过期时间设置为1个小时：`expireSeconds=3600`

开启腾讯云签名选择`开启`，否则选择`关闭`

![](https://cnb.xiaoying.org.cn/img/20260303005703272.png)

`expireSeconds`，过期秒数，默认0（永久）
`sign`，是否开启腾讯云签名，默认关闭



