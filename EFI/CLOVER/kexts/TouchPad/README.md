# 须知
直至 2019-04-11 由于触控板驱动的开发者仍未发布新版（目前为2.1.4），y7000系列的触控板能驱动的前提是自行使用开发者的源码编译的版本，目前10.14.4系统对目前的触控板驱动十分不友好，如果添加了触控驱动导致无限重启，请移除再尝试。建议使用10.13.6版本的系统，目前最稳定。

# 触控板驱动使用说明
1. 将 VoodooI2C_Debug_2.1.5.kext 和 VoodooI2CHID_Debug_2.1.5.kext 移动到 EFI/CLOVER/kexts/Other 中
2. 修复权限重建缓存
3. 重启
