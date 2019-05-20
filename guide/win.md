
# Windows电脑/Windows VPN教程

### 1. 下载并安装Cisco Anyconnect（Windos版本）

下载地址：[Anyconnect-win-4.2.05015](http://dl.vip-vpn.cn:8001/app/anyconnect-win-4.2.05015-pre-deploy-k9.msi)

### 2. 下载完成后，找到下载好的安装文件，双击运行：

![图1-双击运行](http://bqvpn.com/img/guide/win/2.jpg)

### 3. 点击“Next”，进行下一步：

![图2-下一步](http://bqvpn.com/img/guide/win/3.jpg)

### 4. 勾选“I accept the terms in the Lincnse Agreement”，同意服务条款，再点“Next”继续下一步：

![图3-同意服务条款](http://bqvpn.com/img/guide/win/4.jpg)

### 5. 点击“Install”进行安装：

![图4-安装](http://bqvpn.com/img/guide/win/5.jpg)

### 6. 稍等片刻，等待安装过程完成：

![图5-等待安装过程完成](http://bqvpn.com/img/guide/win/6.jpg)

### 7. 点击“Finish”，完成安装：

![图6-完成安装](http://bqvpn.com/img/guide/win/7.jpg)

### 8. 到开始菜单中找到刚安装好的客户端，点击运行：

![图7-运行客户端](http://bqvpn.com/img/guide/win/8.jpg)

!> 注意：Anyconnect安装完成后不会在桌面创建图标，请在开始菜单找到程序Cisco/AnyConnect Secure Mobility client，点击打开。

### 9. 点击客户端左下角“设置”图标更改安全项设置：

![图8-设置](http://bqvpn.com/img/guide/win/9.png)

### 10. 在设置的第一页“Preference”，把最后一项“Block connections to untrusted servers”的勾选去除：

![图9-Preference](http://bqvpn.com/img/guide/win/10.jpg)

?> 这里只是选择信任服务端的https证书，请不用担心，这样操作本身不会有任何安全隐患，只是避免了繁琐的导入证书而已（如果需要导入证书以避免安全告警的，也可以联系客服QQ：10193218咨询）。

### 11. 填写VPN服务器地址（请联系客服索取），点击“Connect”开始连接，之后会提示要求输入用户名、密码，按要求操作即可：

![图10-服务器地址](http://bqvpn.com/img/guide/win/11.jpg)

### 12. 连接成功：

![图11-连接成功](http://bqvpn.com/img/guide/win/12.png)  

?> 连接成功后，电脑网络即开启全局VPN隧道连接，用浏览器或其他任何软件访问网络都将通过VPN中转。

!> 其他可能出现的情况：
如果登录前没有进行第9步的更改设置，可能会弹出如下提示：
![图12-更改设置](http://bqvpn.com/img/guide/win/plus.jpg)  
此时需要点击如图所示“Change Setting”，然后按第10步骤操作设置一下即可。
