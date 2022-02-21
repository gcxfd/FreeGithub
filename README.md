# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 34.212.134.181
camo.githubusercontent.com 34.222.128.205
github.map.fastly.net 18.236.134.102
github.global.ssl.fastly.net 18.236.134.102
github.com 35.165.221.123
api.github.com 18.236.155.99
raw.githubusercontent.com 54.190.93.216
favicons.githubusercontent.com 52.33.119.65
avatars5.githubusercontent.com 34.219.209.153
avatars4.githubusercontent.com 18.237.150.189
avatars3.githubusercontent.com 35.165.221.123
avatars2.githubusercontent.com 54.185.195.143
avatars1.githubusercontent.com 34.222.128.205
avatars0.githubusercontent.com 54.190.93.216
# Github Host End
```

更新时间：2022-02-21 09:10:46

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder