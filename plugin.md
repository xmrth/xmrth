## PC端如何通过SwitchyOmega插件来增强代理稳定性
> 可解决90%忽然连不上外网的问题！

**第一步：安装SwitchyOmega插件**：

- 【推荐】Edge浏览器安装方法：[点此跳转](https://microsoftedge.microsoft.com/addons/detail/proxy-switchyomega/fdbloeknjpnloaggplaobopplkdhnikc?hl=zh-CN)插件页面并点击安装
- Chrome浏览器安装方法：[点此打开](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif?hl=zh-CN)应用商店点【添加至Chrome】；如果无法访问应用商店，请尝试反复开关Clash面板的“系统代理开关”。

**第二步：设置proxy模式**
- 先在浏览器地址栏右侧插件区找到switchyomega插件图标（圆环）上左键点一下，弹出下图，点选项进入设置：
![image](https://user-images.githubusercontent.com/98644184/162599930-01aafd7f-7cb2-442e-b066-ba4a3ae5f100.png)
- 设置proxy情景模式，关键点：【SOCKS5--127.0.0.1--端口】
> - Clash的代理端口是7890
> - v2rayN的代理端口是10808

![1621324184740842](https://user-images.githubusercontent.com/109172552/192149589-4fbbc1a0-8437-4739-a287-73936f3802db.png)

**第三步，切换代理模式即可上网（一定要切换不然用不了）**：
在浏览器地址栏右侧找到圆圈状的SwitchyOmega插件图标，左键点击后出现以下菜单，然后点【系统代理】或者【Proxy】：
![1627050489338408](https://user-images.githubusercontent.com/109172552/192149600-245dc1cb-e927-4674-a1ee-b3f014924209.png)


**最后确认**：
务必访问 chrome://settings/system 确认 [代理设置] 一项必须显示 [此设置由“Proxy SwitchyOmega”控制]，否则请关闭其他插件重新打开 ProxySwitchyOmega！

> **模式说明：**
> 【系统代理】开启VPN并打开VPN的系统代理模式时，浏览器走代理，关闭时直连。
> 【proxy】强行开启代理（代理更稳定，但VPN没启动时无法上网）
> 【直接连接】关闭代理（如果无法上网，显示代理服务器有问题，可以用这个恢复国内上网功能）
