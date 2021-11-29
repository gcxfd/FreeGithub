# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 34.219.243.94
camo.githubusercontent.com 52.13.40.208
github.map.fastly.net 35.85.143.225
github.global.ssl.fastly.net 20.114.9.148
github.com 52.41.80.246
api.github.com 34.219.243.94
raw.githubusercontent.com 54.188.48.208
favicons.githubusercontent.com 35.85.220.98
avatars5.githubusercontent.com 18.236.106.66
avatars4.githubusercontent.com 52.27.93.238
avatars3.githubusercontent.com 54.184.133.192
avatars2.githubusercontent.com 54.188.48.208
avatars1.githubusercontent.com 35.85.143.225
avatars0.githubusercontent.com 34.219.124.158
# Github Host End
```

更新时间：2021-11-29 09:06:59

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder