# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 3.230.76.41
camo.githubusercontent.com 54.242.115.105
github.map.fastly.net 3.230.151.189
github.global.ssl.fastly.net 3.84.117.117
github.com 3.238.138.25
api.github.com 44.193.4.120
raw.githubusercontent.com 100.27.1.143
favicons.githubusercontent.com 100.24.117.11
avatars5.githubusercontent.com 54.242.115.105
avatars4.githubusercontent.com 54.161.9.135
avatars3.githubusercontent.com 54.152.83.28
avatars2.githubusercontent.com 50.19.204.77
avatars1.githubusercontent.com 20.122.139.47
avatars0.githubusercontent.com 44.200.251.234
# Github Host End
```

更新时间：2021-12-20 09:11:50

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder