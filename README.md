# FreeGithub
自动获取github相关网站的ip地址，解决github链接不畅通的问题，该项目的README会自动更新，大家可以直接复制使用。
在workflows/freegithub.yml文件中可以设置自动更新的时间，本代码设置的是一个月自动更新一次。大家可以按照自己的需求改写cron表达式

## hosts列表
```base
#Github Host Start
github.githubassets.com 3.88.249.119
camo.githubusercontent.com 44.192.115.208
github.map.fastly.net 34.207.177.40
github.global.ssl.fastly.net 52.91.239.43
github.com 34.204.92.194
api.github.com 3.91.193.94
raw.githubusercontent.com 23.22.238.201
favicons.githubusercontent.com 44.201.21.80
avatars5.githubusercontent.com 3.82.188.196
avatars4.githubusercontent.com 52.91.239.43
avatars3.githubusercontent.com 3.234.215.242
avatars2.githubusercontent.com 3.82.188.196
avatars1.githubusercontent.com 34.207.177.40
avatars0.githubusercontent.com 54.234.153.180
# Github Host End
```

更新时间：2022-02-14 09:08:29

## 修改本机的hosts文件
### 存放位置
* Windows 系统：C:\Windows\System32\drivers\etc\hosts
* Linux 系统：/etc/hosts
* Mac（苹果电脑）系统：/etc/hosts

### 生效
* Windows：在 CMD 窗口输入：ipconfig /flushdns
* Linux 命令：sudo rcnscd restart
* Mac 命令：sudo killall -HUP mDNSResponder