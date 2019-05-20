# Windows版常见问题：

### 1. 登录不上，报“Failed to get configuration...”错误：
![Failed to get configuration...](http://bqvpn.com/img/faq/win/failed_to_get_config.png)  

目前发现Win10版本升级某些特定的补丁包后会报这个错误，官方尚未找最终的解决方法，不过可以先按以下方式解决：找到目录C:\ProgramData\Cisco\Cisco AnyConnect Secure Mobility Client\Profile，删除它下面的profile.xml文件，再打开Cisco Anyconnect客户端重新填入服务器地址即可。

### 2. 卸载不掉、卸载不干净的问题：
卸载Cisco AnyConnect Secure Mobility Client需要找到原安装包（找不到包的可以先到下载页面下载），双击运行，稍候会提示操作类型，此时选择“Remove”即可。  

![uninstall](http://bqvpn.com/img/faq/win/uninstall.png)
