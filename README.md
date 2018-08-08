# MSCOMM32
This is share for MSCOMM32.OCX install trick

Tested with WINSOWS10(64bit) with OFFICE2016(32bit). It should worked at any system.

## How to Use
1. Copy **MSCOMM32.OCX** to **C:\WINDOWS\SysWOW64** (If you using 32bit Windows to **C:\WINDOWS\SysWOW32** ) 

2. Run CMD(As Administrator)
```
regsvr32 /u C:\WINDOWS\SysWOW64\MSCOMM32.OCX
regsvr32 /i C:\WINDOWS\SysWOW64\MSCOMM32.OCX
regsvr32 C:\WINDOWS\SysWOW64\MSCOMM32.OCX
```

3. Double click **Regedit_MSCOMM32.reg**

enjoy!

## 使用方法
1. 复制 **MSCOMM32.OCX** 到 **C:\WINDOWS\SysWOW64** (如果是32位系统就是 **C:\WINDOWS\SysWOW32** )

2. 依次运行下面三条命令(以管理员身份运行)：
```
regsvr32 /u C:\WINDOWS\SysWOW64\MSCOMM32.OCX
regsvr32 /i C:\WINDOWS\SysWOW64\MSCOMM32.OCX
regsvr32 C:\WINDOWS\SysWOW64\MSCOMM32.OCX
```

3. 运行注册控件：
**Regedit_MSCOMM32.reg**

恭喜可以正常使用MSCOMM32控件了！~
