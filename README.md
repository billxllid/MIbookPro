# Tips

## Update

1. 如果感觉触控板不好用了, 可以包原来包里面`/EFI/CLOVER/kexts/Other/VoodooI2C.kext`和`/EFI/CLOVER/kexts/Other/VoodooI2CHID.kext`到对应目录下, 替换一下
2. 蓝牙不能用了, 将`/EFI/CLOVER/kexts/Other/USBPower.kext`替换一下
3. 忘记怎么加串码, 可以看文件里面的说明`EFI-Clover替换说明.pdf`
4. 快捷键问题用`Karabiner-elements`解决, profile可以在附件里`快捷键`找到
5. 挂载EFI的方法：打开终端，输入命令：sudo diskutil mount disk0s1或者sudo diskutil mount EFI
