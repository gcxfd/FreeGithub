# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 54.244.150.123
camo.githubusercontent.com 35.88.119.86
github.map.fastly.net 35.88.119.86
github.global.ssl.fastly.net 52.40.124.91
github.com 35.161.122.209
api.github.com 35.161.122.209
raw.githubusercontent.com 35.167.53.1
favicons.githubusercontent.com 54.218.221.122
avatars5.githubusercontent.com 35.167.53.1
avatars4.githubusercontent.com 35.87.20.24
avatars3.githubusercontent.com 34.214.160.124
avatars2.githubusercontent.com 35.167.221.235
avatars1.githubusercontent.com 18.236.63.108
avatars0.githubusercontent.com 34.214.160.124
# Github Host End
```

更新时间：2022-01-17 09:14:38

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder