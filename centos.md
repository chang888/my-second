## 搭建apache

- 用putty 密码登录的时候 输入密码没反应 (更轻量化)
- 换了xhell 直接输入用户名密码 登录(相对大一点功能 更全) 其实安装Apache就是 安装httpd
- 1 安装 指令  yum install httpd 然后y 完成
- 2 开启服务 指令 
  systemctl start httpd.service
- 停止服务 指令 systemctl stop httpd.service
- 3 配置Apache服务 vi/etc/httpd/conf/httpd.conf
  修改如下数据 #Listen 12.34.56.78.80 模仿更改 写上你的ip或者域名,本地访问ip地址为127.0.0.1, 如果有报错 就按照系统的提示 一步一步解决.
- 4 如果有域名直接在server NAME
- 5 访问你的服务器地址 如果显示Apache的测试页就说明启动成功了
- 6 系统如果提示httpd已经开启,可以结束所有httpd服务,再重新开启.
  killall httpd
  systemctl start httpd.service





