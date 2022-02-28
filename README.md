# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 35.88.191.220
camo.githubusercontent.com 35.165.179.235
github.map.fastly.net 54.200.43.226
github.global.ssl.fastly.net 54.70.5.224
github.com 35.86.127.61
api.github.com 35.88.191.220
raw.githubusercontent.com 35.88.135.48
favicons.githubusercontent.com 34.223.251.207
avatars5.githubusercontent.com 54.202.196.122
avatars4.githubusercontent.com 34.223.252.45
avatars3.githubusercontent.com 54.202.61.193
avatars2.githubusercontent.com 52.27.161.85
avatars1.githubusercontent.com 54.245.217.116
avatars0.githubusercontent.com 54.200.43.226
# Github Host End
```

更新时间：2022-02-28 09:19:26

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder