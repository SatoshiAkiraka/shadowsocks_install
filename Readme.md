# Auto install Shadowsocks Server

使用方法
使用root用户登录，运行以下命令：

wget --no-check-certificate -O shadowsocks-libev.sh https://github.com/SatoshiAkiraka/shadowsocks_install/raw/master/shadowsocks-libev.sh

chmod +x shadowsocks-libev.sh

./shadowsocks-libev.sh 2>&1 | tee shadowsocks-libev.log




安装完成后，脚本提示如下

Congratulations, your_shadowsocks_version install completed!

Your Server IP        :
your_server_ip

Your Server Port      :
your_server_port

Your Password         :
your_password

Your Encryption Method:aes-256-cfb


Welcome to visit:https://teddysun.com/486.html

Enjoy it!



卸载方法

若已安装多个版本，则卸载时也需多次运行（每次卸载一种）
使用root用户登录，运行以下命令：

./shadowsocks-all.sh uninstall



启动脚本

启动脚本后面的参数含义，从左至右依次为：启动，停止，重启，查看状态。

Shadowsocks-Python 版：
/etc/init.d/shadowsocks-python start | stop | restart | status

ShadowsocksR 版：
/etc/init.d/shadowsocks-r start | stop | restart | status

Shadowsocks-Go 版：
/etc/init.d/shadowsocks-go start | stop | restart | status

Shadowsocks-libev 版：
/etc/init.d/shadowsocks-libev start | stop | restart | status



各版本默认配置文件

Shadowsocks-Python 版：
/etc/shadowsocks-python/config.json

ShadowsocksR 版：
/etc/shadowsocks-r/config.json

Shadowsocks-Go 版：
/etc/shadowsocks-go/config.json

Shadowsocks-libev 版：
/etc/shadowsocks-libev/config.json





Copyright (C) 2014-2018 Teddysun
