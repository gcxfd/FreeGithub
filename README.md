# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 44.193.73.15
camo.githubusercontent.com 3.92.228.196
github.map.fastly.net 174.129.149.182
github.global.ssl.fastly.net 54.196.99.145
github.com 34.229.183.158
api.github.com 3.91.63.123
raw.githubusercontent.com 44.201.44.78
favicons.githubusercontent.com 44.193.73.240
avatars5.githubusercontent.com 18.209.221.254
avatars4.githubusercontent.com 52.90.233.245
avatars3.githubusercontent.com 3.83.192.29
avatars2.githubusercontent.com 107.22.16.234
avatars1.githubusercontent.com 100.26.51.108
avatars0.githubusercontent.com 18.209.221.254
# Github Host End
```

更新时间：2022-03-21 09:41:19

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder