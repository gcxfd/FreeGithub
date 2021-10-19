# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 34.221.60.255
camo.githubusercontent.com 35.167.36.109
github.map.fastly.net 54.186.218.89
github.global.ssl.fastly.net 34.221.60.255
github.com 34.221.62.101
api.github.com 54.202.195.82
raw.githubusercontent.com 54.202.195.82
favicons.githubusercontent.com 54.245.45.87
avatars5.githubusercontent.com 54.245.45.87
avatars4.githubusercontent.com 54.149.48.179
avatars3.githubusercontent.com 54.189.112.179
avatars2.githubusercontent.com 35.164.133.210
avatars1.githubusercontent.com 34.209.28.109
avatars0.githubusercontent.com 54.202.195.82
# Github Host End
```

更新时间：2021-10-19 12:08:15

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder