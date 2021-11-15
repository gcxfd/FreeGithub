# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 34.216.245.239
camo.githubusercontent.com 34.213.251.179
github.map.fastly.net 34.221.116.19
github.global.ssl.fastly.net 18.236.242.146
github.com 18.236.92.232
api.github.com 54.244.141.201
raw.githubusercontent.com 54.188.191.117
favicons.githubusercontent.com 54.244.141.201
avatars5.githubusercontent.com 34.215.119.112
avatars4.githubusercontent.com 54.185.5.178
avatars3.githubusercontent.com 34.221.116.19
avatars2.githubusercontent.com 34.222.51.61
avatars1.githubusercontent.com 54.189.88.62
avatars0.githubusercontent.com 52.25.13.124
# Github Host End
```

更新时间：2021-11-15 09:06:20

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder