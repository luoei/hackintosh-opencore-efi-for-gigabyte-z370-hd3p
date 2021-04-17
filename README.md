# hackintosh-opencore-efi-for-gigabyte-z370-hd3p    
技嘉Z370 HD3P 黑苹果EFI文件(OC版)    
Gigabyte z370 hd3p OpenCore EFI files    
BIOS Version: F14b     

## 已测试OSX版本 Tested OSX    
目前基本完美

##### Big Sur（master branch）
11.2.3   

## 重要说明！ Attention!
请使用**OpenCore Configurator**工具生成一个新的Mac序列号。       
Please use **OpenCore Configurator** to generate new SN.

## 已测试项目 Tested feature
- [x] USB已定制

*1: 建议使用CPUFriend中的Tools重新生成一份属于自己的配置文件。     
*1: Use CPUFriend tools to generate a your profile is recommend!     
https://github.com/acidanthera/CPUFriend/blob/master/Instructions.md     

## 我的配置 My hardware infomation 
- Intel Core i7 8700k
- 技嘉Z370 HD3P
- 光威 弈PRO(合肥长鑫) DDR4 3000 8G x4 
- 致钛(长江存储) 512G
- 华硕AMD RX560 2G
- AOC 27寸4k显示器

## BIOS Settings:	

- BIOS 功能 – 快速启动 – 关闭
- BIOS 功能 – CSM 支持 – 关闭
- 集成外设 – 预设启动的显示设备 – PCEe 插槽 1
- 集成外设 – 4G 以上解码 – 启动
- 集成外设 – Inter Platform Trust Technology(PTT) – 关闭
- 集成外设 – USB 程序 – XHCI Hand-off – 开启
- 芯片组 - VT-d – 关闭
- 芯片组 – 内建显示核心 – 启动
- 芯片组 – DVMT 预载 Pre-Allocated – 128M
- 芯片组 – DVMT Total GFx Mem – 256M
- 电源管理 – RC6(Render Standby) – 启动
