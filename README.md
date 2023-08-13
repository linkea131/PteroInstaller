# ForestRacks 翼手龙安装程序
欢迎来到 ForestRacks Pterodactyl 安装程序存储库！该安装程序专为 ForestRacks 客户而设计，可在基于 Debian 或基于 RHEL 的计算机上轻松安装和设置 Pterodactyl Panel。如果您在安装过程中遇到任何问题，我们的故障排除部分提供了一些有用的提示.

## 安装:
1) 首先，如果您事先对计算机进行了任何更改，请确保重新安装您的计算机，这一点很重要. 
2) 将 DNS A 记录指向您计算机的 IP 地址，例如 panel.forestracks.com 解析到 192.168.53.72.
3) 要下载并运行安装程序，只需在终端中输入以下命令并按照提示操作即可:
```
bash <(curl -Ss https://raw.githubusercontent.com/ForestRacks/PteroInstaller/Production/install.sh || wget -O - https://raw.githubusercontent.com/ForestRacks/PteroInstaller/Production/install.sh) auto
```
## 安装后:
* 请注意 "example.com" 指您在安装过程中设置的面板 URL.
1) 安装完成后，进入http://example.com/admin/nodes/view/1/alloca
2) 为您的游戏添加必要的端口

## 故障排除:
1) 如果您收到 mysql 连接错误，您可能已多次运行安装程序 - 在这种情况下，最好的解决方案是重新安装操作系统并再次运行安装脚本.
2) 如果您遇到 Let's Encrypt SSL 生成错误，可能是因为您使用的是 IP 地址而不是域，或者因为您尝试为其生成 SSL 的 FQDN 没有指向您计算机的 A 记录 IP.

## 兼容的操作系统:
* Ubuntu: 18.04, 20.04, 22.04, 23.04
* CentOS: 7, 8
* AlmaLinux: 8, 9
* Debian: 10, 11, 12

## 贡献者 ✨

我们要感谢以下贡献者在维护和创建此安装程序方面所做的工作:
1) [Zinidia](https://github.com/Zinidia)
2) [Vilhelm Prytz](https://github.com/vilhelmprytz)
3) [ImGreen](https://github.com/GreenDiscord)
3) [Neon](https://github.com/DeveloperNeon)
4) [sam1370](https://github.com/sam1370)
5) [Linux123123](https://github.com/Linux123123)
