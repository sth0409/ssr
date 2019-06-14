# ssr
Cao Ni MA
======


1.Install Wget on CentOs 7
```bash
yum -y install wget
```
2.Install BBR Plus
```bash
wget "https://github.com/caonimagfw/bbrplus/raw/master/ok_bbrplus_centos.sh" && chmod +x ok_bbrplus_centos.sh && ./ok_bbrplus_centos.sh
```
安装后，执行uname -r，显示4.14.89则切换内核成功
执行lsmod | grep bbr，显示有bbrplus则开启成功

3.Install SSR:
```bash
wget --no-check-certificate -O shadowsocksR.sh https://raw.githubusercontent.com/caonimagfw/ssr/master/shadowsocksR.sh && bash shadowsocksR.sh
```



4.Other:

启动：/etc/init.d/shadowsocks start
停止：/etc/init.d/shadowsocks stop
重启：/etc/init.d/shadowsocks restart
状态：/etc/init.d/shadowsocks status
相关文件位置：
配置文件路径：/etc/shadowsocks.json
日志文件路径：/var/log/shadowsocks.log
代码安装目录：/usr/local/shadowsocks


5.New 
```bash
wget --no-check-certificate -O onefast.sh https://raw.githubusercontent.com/caonimagfw/onefast/master/onefast.sh && bash onefast.sh
```
