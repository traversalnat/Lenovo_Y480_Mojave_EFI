# Lenovo_Y480_Catalina_EFI
### macOS15.3 目前不建议升级，所有32位应用程序无法使用，brew尚未适配该系统
### 该EFI 兼容 Mojave
### 声卡alc_269 注入layout_id: 7
### 无线网卡: 自行更换或购买usb网卡, Y480支持AR5B195/AR9285 网卡
###	AR5B195/AR9285 网卡：已将需要的驱动(IO80211Family.kext，IO80211FamilyV2.kext)放入CLOVER中(需删除SLE目录中的同名文件），也可以直接替换SLE的同名文件

### 以下两条指令可将根目录重新挂载为可读写
` sudo spctl --master-disable`

`	sudo mount -uw /`
### 蓝牙: 参考 `https://www.jianshu.com/p/4044c7091f1f` 更换ID
