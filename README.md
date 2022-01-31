# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 20.38.168.102
camo.githubusercontent.com 54.213.25.26
github.map.fastly.net 54.244.105.184
github.global.ssl.fastly.net 20.38.168.102
github.com 34.215.175.186
api.github.com 54.213.25.26
raw.githubusercontent.com 54.191.63.70
favicons.githubusercontent.com 34.215.175.186
avatars5.githubusercontent.com 18.237.168.18
avatars4.githubusercontent.com 34.214.3.192
avatars3.githubusercontent.com 18.237.168.18
avatars2.githubusercontent.com 35.87.99.223
avatars1.githubusercontent.com 18.236.206.47
avatars0.githubusercontent.com 54.191.63.70
# Github Host End
```

更新时间：2022-01-31 09:07:31

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder