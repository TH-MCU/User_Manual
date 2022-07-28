# 下载Keil
[keil官网](https://www.keil.com/download/product/),下载这俩文件即可（可能需要科学上网）
![image](https://user-images.githubusercontent.com/43512109/181462172-2de690b2-af45-4b1b-8068-9985f490175b.png)
```
// 安装目录Tool文件最后一段添加以下内容：【Path中改成你的目录X:\X\C51】
// Version的版本和你下载的要一致
[C51]
PATH="E:\dpj\C51\" 
VERSION=V9.51
BOOK0=HLP\Release_Notes.htm("Release Notes",GEN)
BOOK1=HLP\C51TOOLS.chm("Complete User's Guide Selection",C)
TDRV0=BIN\MON51.DLL ("Keil Monitor-51 Driver")
TDRV1=BIN\ISD51.DLL ("Keil ISD51 In-System Debugger")
TDRV2=BIN\MON390.DLL ("MON390: Dallas Contiguous Mode")
TDRV3=BIN\LPC2EMP.DLL ("LPC900 EPM Emulator/Programmer")
TDRV4=BIN\UL2UPSD.DLL ("ST-uPSD ULINK Driver")
TDRV5=BIN\UL2XC800.DLL ("Infineon XC800 ULINK Driver")
TDRV6=BIN\MONADI.DLL ("ADI Monitor Driver")
TDRV7=BIN\DAS2XC800.DLL ("Infineon DAS Client for XC800")
TDRV8=BIN\UL2LPC9.DLL ("NXP LPC95x ULINK Driver")
RTOS0=Dummy.DLL("Dummy")
RTOS1=RTXTINY.DLL ("RTX-51 Tiny")
RTOS2=RTX51.DLL ("RTX-51 Full")
LIC0=MPYH9-4WK76-ITG3R-K50HC-X5RIT-SKT3T

```

---------------
## 编写完代码后，点击Rebuild，且不报错，则证明没问题，已经生成hex文件了。就可以去下载到单片机中了
## [程序下载教程](https://github.com/TongHaiMCU/User_Manual/blob/3a7cb06df2513e30f926e38888dc7e99f4e82c72/STC%E4%B8%8B%E8%BD%BD%E5%99%A8%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E.md)；
![image](https://user-images.githubusercontent.com/43512109/181453888-b9aacab2-c1f3-4e2a-9cf0-004328550b37.png)
