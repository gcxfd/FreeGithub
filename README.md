# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 54.244.81.75
camo.githubusercontent.com 34.212.0.24
github.map.fastly.net 54.149.227.122
github.global.ssl.fastly.net 54.191.255.143
github.com 34.217.99.249
api.github.com 54.201.151.158
raw.githubusercontent.com 18.236.153.131
favicons.githubusercontent.com 34.212.20.238
avatars5.githubusercontent.com 54.191.228.162
avatars4.githubusercontent.com 54.70.58.171
avatars3.githubusercontent.com 54.70.58.171
avatars2.githubusercontent.com 34.211.58.78
avatars1.githubusercontent.com 35.87.27.254
avatars0.githubusercontent.com 34.212.20.238
# Github Host End
```

更新时间：2022-05-02 10:07:42

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder