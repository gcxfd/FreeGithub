# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 44.200.47.201
camo.githubusercontent.com 52.204.28.86
github.map.fastly.net 54.234.126.157
github.global.ssl.fastly.net 3.230.144.189
github.com 20.94.80.163
api.github.com 34.229.162.20
raw.githubusercontent.com 34.204.170.13
favicons.githubusercontent.com 3.239.35.97
avatars5.githubusercontent.com 54.198.253.119
avatars4.githubusercontent.com 3.81.125.118
avatars3.githubusercontent.com 44.200.218.6
avatars2.githubusercontent.com 3.221.150.161
avatars1.githubusercontent.com 3.229.124.136
avatars0.githubusercontent.com 54.226.174.56
# Github Host End
```

更新时间：2022-03-28 09:47:57

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder