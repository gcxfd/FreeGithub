# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 3.85.191.254
camo.githubusercontent.com 3.85.191.254
github.map.fastly.net 151.101.1.6
github.global.ssl.fastly.net 151.101.1.6
github.com 140.82.112.3
api.github.com 140.82.112.3
raw.githubusercontent.com 18.233.171.48
favicons.githubusercontent.com 3.236.204.177
avatars5.githubusercontent.com 54.146.226.155
avatars4.githubusercontent.com 23.22.233.219
avatars3.githubusercontent.com 54.226.97.147
avatars2.githubusercontent.com 107.23.146.18
avatars1.githubusercontent.com 52.91.84.88
avatars0.githubusercontent.com 3.92.58.45
# Github Host End
```

更新时间：2022-11-28 09:46:14

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder