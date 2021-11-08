# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 34.217.3.221
camo.githubusercontent.com 52.33.96.133
github.map.fastly.net 52.37.124.200
github.global.ssl.fastly.net 34.218.232.166
github.com 18.236.63.134
api.github.com 34.218.232.166
raw.githubusercontent.com 34.218.232.166
favicons.githubusercontent.com 52.13.19.173
avatars5.githubusercontent.com 54.184.57.177
avatars4.githubusercontent.com 34.219.23.88
avatars3.githubusercontent.com 34.219.23.88
avatars2.githubusercontent.com 52.13.19.173
avatars1.githubusercontent.com 52.32.216.210
avatars0.githubusercontent.com 34.219.23.88
# Github Host End
```

更新时间：2021-11-08 09:06:36

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder