# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 18.237.41.212
camo.githubusercontent.com 34.210.200.255
github.map.fastly.net 34.219.90.55
github.global.ssl.fastly.net 35.167.169.240
github.com 35.161.37.59
api.github.com 54.245.149.169
raw.githubusercontent.com 18.237.41.212
favicons.githubusercontent.com 34.210.200.255
avatars5.githubusercontent.com 34.213.248.227
avatars4.githubusercontent.com 35.87.188.166
avatars3.githubusercontent.com 35.86.142.184
avatars2.githubusercontent.com 20.106.72.104
avatars1.githubusercontent.com 35.87.249.134
avatars0.githubusercontent.com 34.213.248.227
# Github Host End
```

更新时间：2021-12-06 09:10:07

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder