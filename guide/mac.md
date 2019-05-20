
# 苹果电脑/Mac VPN教程

### 1. 下载并安装Cisco Anyconnect（Mac版本）

百度网盘下载地址：[Anyconnect-macos](https://pan.baidu.com/s/1nwjWyTz)，密码：u1o4

### 2. 下载完成后，打开下载好的.dmg文件，双击运行：

![图1-双击运行](http://bqvpn.com/img/guide/mac/pkg.png)

### 3. 点击“Continue”，进行下一步：

![图2-introduction](http://bqvpn.com/img/guide/mac/introduction.png)

### 4. 继续点击“Continue”，进行下一步：

![图3-License](http://bqvpn.com/img/guide/mac/license.png)
![图4-Agree License](http://bqvpn.com/img/guide/mac/agree_license.png)

### 5. 点击“Continue”进行安装：

![图5-安装](http://bqvpn.com/img/guide/mac/install.png)

?>只需勾选VPN选项即可。

![图6-授权安装](http://bqvpn.com/img/guide/mac/install_authorize.png)

### 7. 点击“Close”，完成安装：

![图7-完成安装](http://bqvpn.com/img/guide/mac/summary.png)

### 8. 视用户系统版本情况，可能会看到如下提示“是否删除安装包？”，建议选择“Move to Trash”删除安装包以节省空间：

![图8-删除安装包](http://bqvpn.com/img/guide/mac/delete_package.png)

### 9. 至此客户端安装完毕，到应用程序文件夹 > Cisco > Cisco AnyConnect Secure Mobility Client，双击运行：

![图9-运行客户端-1](http://bqvpn.com/img/guide/mac/run_1.png)
![图10-运行客户端-2](http://bqvpn.com/img/guide/mac/run_2.png)

### 10. 点击客户端左下角“设置”图标更改安全项设置：

![图11-设置](http://bqvpn.com/img/guide/mac/setting.png)

### 11. 在设置的第一页“Preference”，把最后一项“Block connections to untrusted servers”的勾选去除：

![图12-Preference](http://bqvpn.com/img/guide/win/10.jpg)

?> 这里只是选择信任服务端的https证书，请不用担心，这样操作本身不会有任何安全隐患，只是避免了繁琐的导入证书步骤而已（如果需要导入证书以避免安全告警的，也可以联系客服QQ：10193218咨询）。

### 12. 填写VPN服务器地址（请联系客服索取），点击“Connect”开始连接，之后会提示要求输入用户名、密码，按要求操作即可：

![图13-服务器地址](http://bqvpn.com/img/guide/mac/server_address.png)

### 13. 连接成功：

?> 连接成功后，电脑网络即开启全局VPN隧道连接，用浏览器或其他任何软件访问网络都将通过VPN中转。

!> 其他可能出现的情况：

如果登录前没有进行第10步的更改设置，可能会弹出如下提示：
![图12-](http://bqvpn.com/img/guide/win/plus.jpg)

此时需要点击如图所示“Change Setting”，然后按第11步操作设置一下即可。
