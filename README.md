# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 18.236.194.53
camo.githubusercontent.com 34.220.127.252
github.map.fastly.net 35.167.245.28
github.global.ssl.fastly.net 34.208.185.22
github.com 35.88.238.140
api.github.com 35.88.163.98
raw.githubusercontent.com 34.220.252.20
favicons.githubusercontent.com 54.71.229.131
avatars5.githubusercontent.com 35.164.68.84
avatars4.githubusercontent.com 34.220.171.38
avatars3.githubusercontent.com 54.149.59.125
avatars2.githubusercontent.com 54.214.126.112
avatars1.githubusercontent.com 35.88.163.98
avatars0.githubusercontent.com 35.166.165.54
# Github Host End
```

更新时间：2021-12-13 09:09:16

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder