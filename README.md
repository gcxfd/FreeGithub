# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 44.200.64.201
camo.githubusercontent.com 3.227.253.189
github.map.fastly.net 151.101.1.6
github.global.ssl.fastly.net 151.101.1.6
github.com 140.82.114.3
api.github.com 140.82.114.3
raw.githubusercontent.com 44.210.120.252
favicons.githubusercontent.com 34.226.141.219
avatars5.githubusercontent.com 3.235.225.95
avatars4.githubusercontent.com 100.24.126.174
avatars3.githubusercontent.com 100.24.126.174
avatars2.githubusercontent.com 52.55.211.40
avatars1.githubusercontent.com 18.232.105.13
avatars0.githubusercontent.com 3.238.175.98
# Github Host End
```

更新时间：2023-02-20 09:44:56

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder