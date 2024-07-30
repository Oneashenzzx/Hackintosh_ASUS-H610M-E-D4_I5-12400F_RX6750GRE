适用于 12400F + 华硕H610M-E D4 + RX6750GRE 黑苹果EFI引导文件

基于 OpenCore 0.9.5 版本，机型 MacPro 7,1，系统 MacOS 12.3.1

本EFI修改自https://github.com/huzhimaye/Hackintosh_MS-H610ITX_I5-12400F_RX6750GRE

感谢这位老哥的付出：）

7.30更新，修复了SATA设备不识别的问题
使用EFI时，请将Hackintosh_ASUS-H610M-E-D4_I5-12400F_RX6750GRE/EFI/OC/Kexts/CtlnaAHCIPort.kext.rar解压，我嫌上传文件夹麻烦

【正常驱动功能】

	声卡

	USB接口

	音量调节

	有线网卡

	睡眠唤醒

	CPU睿频

【异常驱动功能】

	由于没有安装独立网卡，蓝牙、隔空投送、接力可用性未知

	RX6750GRE的DRM内容无法正常播放，目前等待驱动修复https://github.com/ChefKissInc/NootRX

	随航

备注

	请不要忘记自行生成三码

配置

	主板：华硕PRIME H610M-E D4

	CPU：英特尔Core i5-12400F

	内存：海盗船 复仇者 LPX 16GB（2x8GB）DDR4 2400MHz C14 成套内存

	显卡：讯景 AMD RX6750GRE 海外版 12GB

	电源：电源 酷冷至尊V550 额定550W

	显示器：创维 F27G4Q（K7E面板） 27英寸 2K 170Hz

固态硬盘（NVME协议）：

	英特尔 SSD 760P 512GB
 
	凯侠RC20 2TB
 
	梵想S500PRO 2TB

NVME硬盘盒USB3.1Gen1：

	凯侠SD10 2TB
 
固态硬盘（SATA协议）：

	梵想FP325T 2TB
 
	镁光M600 1TB
 
机械硬盘：

	希捷 酷鹰 ST6000VX001 6TB
 
	西部数据 蓝盘 WD10EZEX 1TB x2

BIOS设置

打开Above 4G Decoding

打开Re-size BAR Support

打开XHCI Hand-off

关闭Security Device Support

关闭Serial Port

关闭CSM support

关闭Fast Boot

关闭Secure Boot

无需设置CFG Lock，BIOS中也没有该选项

<div style="align: center">
<img src="https://github.com/Oneashenzzx/Hackintosh_ASUS-H610M-E-D4_I5-12400F_RX6750GRE/blob/main/readme/1.png">
</div>

<div style="align: center">
<img src="https://github.com/Oneashenzzx/Hackintosh_ASUS-H610M-E-D4_I5-12400F_RX6750GRE/blob/main/readme/2.png">
</div>

<div style="align: center">
<img src="https://github.com/Oneashenzzx/Hackintosh_ASUS-H610M-E-D4_I5-12400F_RX6750GRE/blob/main/readme/3.png">
</div>

<div style="align: center">
<img src="https://github.com/Oneashenzzx/Hackintosh_ASUS-H610M-E-D4_I5-12400F_RX6750GRE/blob/main/readme/4.png">
</div>

<div style="align: center">
<img src="https://github.com/Oneashenzzx/Hackintosh_ASUS-H610M-E-D4_I5-12400F_RX6750GRE/blob/main/readme/5.png">
</div>

<div style="align: center">
<img src="https://github.com/Oneashenzzx/Hackintosh_ASUS-H610M-E-D4_I5-12400F_RX6750GRE/blob/main/readme/6.png">
</div>

<div style="align: center">
<img src="https://github.com/Oneashenzzx/Hackintosh_ASUS-H610M-E-D4_I5-12400F_RX6750GRE/blob/main/readme/7.png">
</div>

<div style="align: center">
<img src="https://github.com/Oneashenzzx/Hackintosh_ASUS-H610M-E-D4_I5-12400F_RX6750GRE/blob/main/readme/8.png">
</div>

<div style="align: center">
<img src="https://github.com/Oneashenzzx/Hackintosh_ASUS-H610M-E-D4_I5-12400F_RX6750GRE/blob/main/readme/9.png">
</div>
