## MSI PRO Z690 A WIFI DDR4 黑苹果 OpenCore EFI

![image](Screenshot/MSIZ690.jpg)

[OpenCore 0.9.7](https://github.com/acidanthera/OpenCorePkg)


### macOS

- Monterey
- Ventura
- Sonoma


### 硬件

- 芯片组: Z690
- 处理器: 英特尔14代 i7-14700K
- 内   存:  金百达 32GB（16GB*2） DDR4 3200Mhz
- 硬   盘:  致钛TiPlus 1TB MacOS
- 核   显:  英特尔超核心显卡770 (仅能在 Windows中使用)
- 显   卡:  华擎 Radeon RX6650XT
- 声   卡:  瑞昱 ALC897
- 有线网卡: 英特尔 L225-V
- 无线网卡：T919


### BIOS设置

```
1.关闭安全启动
Settings
  |-- Security
     |-- Secure Boot
       |-- Secure Boot: Disabled

2.使用搜索功能查找并启用 D.T.M 
Search
  |-- D.T.M
    |-- D.T.M: Enabled

```

<img src="Screenshot/Search.png" alt="image" style="zoom:50%;" />

<img src="Screenshot/D.T.M.png" alt="image" style="zoom:50%;" />

<img src="Screenshot/SecureBoot.png" alt="image" style="zoom:50%;" />



### 注意事项

 - 安装成功后必须使用 [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) 或者 [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) 生成你自己的 SMBIOS
 - 如需使用没有小核心的CPU，必须取消勾选配置文件中Kernel--ProvideCurrentCpuinfo选项


### 常用工具

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) AKA `OCAT`.
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) AKA `OCC`.
- [gibMacOS](https://github.com/corpnewt/gibMacOS) Build your own MacOS image.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.


### 联系我们

QQ Group: 23304408

![image](Screenshot/QRCode.png)
