# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 35.175.200.161
camo.githubusercontent.com 54.172.28.130
github.map.fastly.net 34.229.22.183
github.global.ssl.fastly.net 3.219.168.201
github.com 18.207.132.10
api.github.com 18.209.111.55
raw.githubusercontent.com 44.203.197.36
favicons.githubusercontent.com 54.144.168.142
avatars5.githubusercontent.com 3.219.168.201
avatars4.githubusercontent.com 18.207.97.99
avatars3.githubusercontent.com 3.236.74.234
avatars2.githubusercontent.com 44.200.234.103
avatars1.githubusercontent.com 54.205.195.211
avatars0.githubusercontent.com 34.228.7.212
# Github Host End
```

更新时间：2022-04-18 10:01:10

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder