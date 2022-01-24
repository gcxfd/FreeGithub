# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 54.164.146.70
camo.githubusercontent.com 100.26.181.89
github.map.fastly.net 44.198.170.53
github.global.ssl.fastly.net 3.236.170.60
github.com 44.192.51.80
api.github.com 3.236.170.60
raw.githubusercontent.com 54.209.76.82
favicons.githubusercontent.com 54.145.162.32
avatars5.githubusercontent.com 44.200.135.159
avatars4.githubusercontent.com 35.172.128.243
avatars3.githubusercontent.com 3.236.100.53
avatars2.githubusercontent.com 184.73.67.119
avatars1.githubusercontent.com 18.208.182.160
avatars0.githubusercontent.com 44.201.150.61
# Github Host End
```

更新时间：2022-01-24 09:09:34

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder