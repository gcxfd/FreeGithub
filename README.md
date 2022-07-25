# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 18.234.41.97
camo.githubusercontent.com 18.212.135.116
github.map.fastly.net 151.101.1.6
github.global.ssl.fastly.net 151.101.1.6
github.com 140.82.112.4
api.github.com 140.82.112.4
raw.githubusercontent.com 18.207.240.28
favicons.githubusercontent.com 44.197.251.123
avatars5.githubusercontent.com 44.204.200.104
avatars4.githubusercontent.com 3.84.91.223
avatars3.githubusercontent.com 3.239.14.157
avatars2.githubusercontent.com 54.159.26.208
avatars1.githubusercontent.com 35.173.250.20
avatars0.githubusercontent.com 54.86.103.223
# Github Host End
```

更新时间：2022-07-25 10:11:25

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder