# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 35.86.138.167
camo.githubusercontent.com 18.237.14.141
github.map.fastly.net 151.101.1.6
github.global.ssl.fastly.net 
github.com 140.82.112.3
api.github.com 140.82.112.3
raw.githubusercontent.com 52.38.183.192
favicons.githubusercontent.com 35.89.215.15
avatars5.githubusercontent.com 35.91.22.131
avatars4.githubusercontent.com 34.214.81.220
avatars3.githubusercontent.com 54.200.160.34
avatars2.githubusercontent.com 35.163.241.153
avatars1.githubusercontent.com 34.222.171.35
avatars0.githubusercontent.com 34.222.171.35
# Github Host End
```

更新时间：2023-01-02 09:35:24

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder