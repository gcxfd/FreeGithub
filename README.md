# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 35.161.140.158
camo.githubusercontent.com 34.215.180.175
github.map.fastly.net 34.212.144.63
github.global.ssl.fastly.net 34.212.230.143
github.com 34.219.84.4
api.github.com 34.221.198.35
raw.githubusercontent.com 34.221.202.214
favicons.githubusercontent.com 18.236.73.16
avatars5.githubusercontent.com 34.215.180.175
avatars4.githubusercontent.com 54.189.153.156
avatars3.githubusercontent.com 35.161.140.158
avatars2.githubusercontent.com 18.237.162.17
avatars1.githubusercontent.com 18.236.73.16
avatars0.githubusercontent.com 18.237.162.17
# Github Host End
```

更新时间：2021-11-22 09:07:46

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder