# btpanel-v7.7.0
btpanel-v7.7.0-backup  官方原版v7.7.0版本面板备份
宝塔面板开心版|企业版|破解版搭建，可视化管理！，简单搭建属于自己的个人网站wordpress博客搭建。安全高效的服务器运维面板，去除登录验证，保护个人私隐

准备工作

下载并安装SSH连接工具Finalshell：[点击进入](https://www.hostbuf.com/t/988.html)
准备一个域名并托管到Cloudflare：[点击进入](https://dash.cloudflare.com/login)

1、关闭防火墙
sudo ufw disable
2、更新系统
apt update -y && apt upgrade -y
3、宝塔官网：[点击进入](https://www.bt.cn/)

**Centos/Ubuntu/Debian安装命令 独立运行环境**

**安装开心版**

```Bash
curl -sSO https://raw.githubusercontent.com/8838/btpanel-v7.7.0/main/install/install_panel.sh && bash install_panel.sh
```

**备用安装链接，适用于不能访问GitHub的服务器。文件公开存放在[d.moe.ms](http://d.moe.ms/?btpanel-v7.7.0)**

```
curl -sSO http://d.moe.ms/AAAAA/btpanel-v7.7.0/install/install_panel.sh && bash install_panel.sh
```

**一键关闭登录验证**

```
wget -O optimize.sh http://f.cccyun.cc/bt/optimize.sh && bash optimize.sh
```

**启动开心版**

```
curl -sSO https://raw.githubusercontent.com/ztkink/bthappy/main/one_key_happy.sh && bash one_key_happy.sh
```

