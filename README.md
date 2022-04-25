# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 35.87.18.50
camo.githubusercontent.com 35.87.18.50
github.map.fastly.net 54.202.19.195
github.global.ssl.fastly.net 35.86.117.188
github.com 54.202.19.195
api.github.com 54.202.142.94
raw.githubusercontent.com 34.214.68.54
favicons.githubusercontent.com 18.236.232.39
avatars5.githubusercontent.com 34.213.6.90
avatars4.githubusercontent.com 35.86.117.188
avatars3.githubusercontent.com 18.237.155.233
avatars2.githubusercontent.com 34.221.120.2
avatars1.githubusercontent.com 52.24.3.87
avatars0.githubusercontent.com 34.222.101.81
# Github Host End
```

更新时间：2022-04-25 09:51:55

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder