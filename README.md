# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 35.88.93.164
camo.githubusercontent.com 34.213.51.111
github.map.fastly.net 34.213.182.32
github.global.ssl.fastly.net 34.213.51.111
github.com 34.213.182.32
api.github.com 34.216.103.122
raw.githubusercontent.com 54.214.150.227
favicons.githubusercontent.com 35.85.217.27
avatars5.githubusercontent.com 54.214.81.78
avatars4.githubusercontent.com 54.201.161.168
avatars3.githubusercontent.com 54.214.81.78
avatars2.githubusercontent.com 34.222.240.223
avatars1.githubusercontent.com 34.213.180.181
avatars0.githubusercontent.com 52.40.149.69
# Github Host End
```

更新时间：2022-05-09 10:01:37

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder