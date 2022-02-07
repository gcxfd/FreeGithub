# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 52.11.124.190
camo.githubusercontent.com 54.184.208.133
github.map.fastly.net 35.161.106.150
github.global.ssl.fastly.net 35.88.105.224
github.com 35.88.105.224
api.github.com 18.237.156.186
raw.githubusercontent.com 18.237.1.226
favicons.githubusercontent.com 35.88.105.224
avatars5.githubusercontent.com 54.212.21.183
avatars4.githubusercontent.com 18.237.154.230
avatars3.githubusercontent.com 34.212.129.117
avatars2.githubusercontent.com 54.200.225.117
avatars1.githubusercontent.com 35.161.106.150
avatars0.githubusercontent.com 54.188.125.152
# Github Host End
```

更新时间：2022-02-07 09:09:44

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder