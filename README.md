# 介绍
参考很多师傅写的关于CS的脚本,内容有横向移动、密码抓取、权限提升、权限维持等,尽可能将内网渗透中常用到的东西整理一下方便使用

## 更新日志

2021.7.7 更新CVE-2021-1675(只测试了本地提权,其他的待测) 参考于 https://github.com/cube0x0/CVE-2021-1675

2021.7.26 更新CVE-2021-1675-36934,参考与 https://github.com/cube0x0/CVE-2021-36934

2021.8.14 更新ZeroLogon(CVE-2020-1472),参考 https://github.com/rsmudge/ZeroLogon-BOF ,失败的话尝试下让Beacon以X64上线

更新RegSave,通过Bof形式无文件Dump注册表,参考 https://github.com/EncodeGroup/BOF-RegSave

## 其他

在实战中发现,如何快速的在一台拿下的机器中搜集登录过的主机、和谁登录过此主机较为重要,于是在 信息搜集 模块中的 RDP 子模块中整合了一下
