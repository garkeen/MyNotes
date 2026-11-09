计算机断电后还有两个部件需要持续供电，一个是CMOS RAM,一个是RTC时钟



### BIOS（Basic Input Output System）

主要做POST （Power-On Self-Test） 加电自检。

简单的来说，就是读取CMOS RAM的内容，识别硬件，初始化









### UEFI

传统BIOS使用汇编编写，而且还需要反复在实模式和保护模式跳转

Intel发明了EFI，然后是UEFI，可以使用c语言写