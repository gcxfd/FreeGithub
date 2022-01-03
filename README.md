# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 54.92.229.164
camo.githubusercontent.com 3.239.11.35
github.map.fastly.net 3.84.54.17
github.global.ssl.fastly.net 3.238.193.22
github.com 20.65.38.4
api.github.com 35.175.131.19
raw.githubusercontent.com 52.206.106.125
favicons.githubusercontent.com 3.92.152.186
avatars5.githubusercontent.com 3.234.146.234
avatars4.githubusercontent.com 20.65.38.4
avatars3.githubusercontent.com 44.192.90.153
avatars2.githubusercontent.com 3.237.28.154
avatars1.githubusercontent.com 44.193.198.91
avatars0.githubusercontent.com 34.239.130.204
# Github Host End
```

更新时间：2022-01-03 09:11:52

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder