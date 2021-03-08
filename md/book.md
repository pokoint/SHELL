# 📑 book.sh

## 脚本介绍

自用

### 脚本版本
**最新版本：** v1.0.0  

### 系统要求
CentOS 6+ / Debian 6+ / Ubuntu 14.04 +  

****

## 下载安装

!> **注意：**因为涉及防火墙端口开关、服务脚本安装，所以脚本需要以 ROOT 用户执行。

``` bash
# 如果你不是 ROOT 用户，请执行下面这行代码切换为 ROOT 用户。  
# 如果你已经是 ROOT 用户了，那么请跳过下面这行代码！

sudo su

# 执行上面一行代码后会提示你输入当前用户的密码，回车后没有报错即可继续。
```

****

?> 如果你要更新脚本，除了使用脚本中的 **[0. 更新脚本]** 功能以外，还可以再次输入下面这一行代码。

执行下面一行代码下载并运行脚本：

``` bash
wget -N --no-check-certificate https://shell.xiu2.xyz/book.sh && chmod +x book.sh && bash book.sh
```

****

### 脚本说明
运行脚本
``` bash
bash book.sh
```
输入对应的数字来执行相应的命令。
``` bash
  Book 一键脚本 [vX.X.X]
  
  0. 更新脚本
----------
  1. 安装
  2. 更新
  3. 卸载
----------
  4. 启动
  5. 停止
  6. 重启
----------
  7. 设置 配置
  8. 查看 账号
  9. 查看 日志
 10. 查看 链接

 当前状态: 已安装 并 已启动

 请输入数字 [0-10]:
 ```

****

### 文件位置
 - **安装目录：**/usr/local/book
 - **日志文件：**/usr/local/book/book.log

 ****
 
### 其他命令
除了用脚本启动、停止、重启以外，还能通过其他命令操作。
 - **启动：**/etc/init.d/book start
 - **停止：**/etc/init.d/book stop
 - **重启：**/etc/init.d/book restart
 - **查看状态：**/etc/init.d/book status
 
 ****
 
## 注意事项

#### 阿里云/腾讯云/微软云/谷歌云等无法连接的可能原因
阿里云/腾讯云/微软云/谷歌云等服务商的云服务器，服务器与网络实际上是分开的，所以分为内网防火墙和外网防火墙，脚本只能修改到内网防火墙，外网防火墙需要你自行去后台寻找 [防火墙/安全规则/端口规则] 等字样相关选项开放代理端口。

****

## 更新日志

#### 2020年08月29日，版本 v1.0.0 :id=100
 - **1. 发布** 第一个版本。  