# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 3.88.240.236
camo.githubusercontent.com 44.198.177.131
github.map.fastly.net 44.199.210.101
github.global.ssl.fastly.net 184.73.14.130
github.com 3.235.171.183
api.github.com 18.206.39.198
raw.githubusercontent.com 52.91.108.59
favicons.githubusercontent.com 18.206.14.199
avatars5.githubusercontent.com 3.235.170.33
avatars4.githubusercontent.com 54.89.254.88
avatars3.githubusercontent.com 20.119.70.228
avatars2.githubusercontent.com 44.197.195.24
avatars1.githubusercontent.com 54.237.98.47
avatars0.githubusercontent.com 3.236.123.165
# Github Host End
```

更新时间：2022-05-16 09:50:54

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder