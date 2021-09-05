# BT_create_web
# 宝塔建站

 ![linolong's GitHub stats](https://github-readme-stats.vercel.app/api?username=linolong&show_icons=true&theme=radical)
 
 ---

## **更新环境：**
 
 apt update -y

## **安装 curl**
 
 apt install -y curl

## **添加dns**
 
 echo 'nameserver 223.5.5.5'>>/etc/resolv.conf 

 echo 'nameserver 223.6.6.6'>>/etc/resolv.conf 

 echo 'nameserver 8.8.8.8'>>/etc/resolv.conf 

 echo 'nameserver 8.8.4.4'>>/etc/resolv.conf 

---
# 安装宝塔

## 安装命令：

> ### centOS

<div class="snippet" markdown="1">

```
yum install -y wget && wget -O install.sh http://download.bt.cn/install/install_6.0.sh && sh install.sh
```

> ### Ubuntu/Debian

<div class="snippet" markdown="1">

```
wget -O install.sh http://download.bt.cn/install/install-ubuntu_6.0.sh && sudo bash install.sh
```

# wordpress

* PHP版本7.3+以上，推荐PHP 7.4

* 数据库MySQL版本5.6+或者MariaDB版本10.1+以上

* nginx或者apache等web服务器

## WordPress下载地址

#### WordPress的官网：

* 英文 https://wordpress.org/
* 中文 https://cn.wordpress.org/

## WordPress的官方下载地址：

* 英文 https://wordpress.org/latest.zip
* 中文 https://cn.wordpress.org/latest-zh_CN.zip

### 方法:
BT界面>>>>文件>>>>远程下载>>>>URL地址：https://cn.wordpress.org/latest-zh_CN.zip >>>>解压>>>>剪切、粘贴

# 内网建站
### 在bt内域名直接输入指定的内网ip地址，建站后局域网便可访问，网站地址为此ip地址

* ## 链接到公盘

* 安装samba

* WINDOWS10如何安装samba3.0

* 首先是兼容SMB lv1协议。打开Control Panel，搜索进入Turn Windows Features on or off。勾选和SMB 1.0/CIFS相关的全部选项。勾选SMB Direct。

* 第二步是开放匿名登陆。打开Control Panel，搜索进入Edit Group Policy。将Computer configuration\administrative templates\network\Lanman Workstation\Enable insecure guest logons设置为Enabled。

### 链接文件地址

<div class="snippet" markdown="1">

```
smb://192.168.x.x/name/???.pdf
```
