# 飞行堡垒6代黑苹果引导文件
v24.03.11.5更新日志：  
1、启用CPUFriend.kext生成CPU动态睿频电源管理数据。  
2、启用HibernationFixup.kext黑苹果睡眠修复。  
3、移除ECEnabler.kext简易电池辅助驱动的系统版本限制（在超出默认支持版本的 macOS 中启用该驱动）。  
4、解决WiFi无法打开的BUG，恢复IntelBTPatcher.kext驱动，提升蓝牙稳定性。  

v24.03.11.4更新日志：  
1、清理多余的引导菜单。  

v24.03.11.3更新日志：  
1、删除和WiFi冲突的IntelBTPatcher.kext驱动。

v24.03.11.2更新日志：  
1、处理WiFi无法打开的BUG。  

v24.03.11.1更新日志：  
1、内嵌新的随机三码，不保证可用性。  

v24.03.11.0更新日志：  
1、新增IntelBTPatcher.kext提升蓝牙稳定性。  
2、新增IntelCPUMonitor.kext实现更多功能。  

v24.03.10.0更新日志：  
1、采用OpenCore0.99 mod正式版，适配最新版Sonoma14.4。  
2、更新全部驱动到最新版。  
3、删除不用的冗余驱动，精简开机启动项，加快开机启动速度。  
4、新注入DisplayInjector.kext，避免显示器适配文件未知。  
5、英特尔网卡和博通均可使用（博通没有实体机测试，理论可行）。  
6、取消OC引导代码，内嵌三款主题，支持自行切换，也可以替换自用主题，PickerVariant>AppleSilicon\Heikintosh\GoldenGate。  
7、内嵌三码仅用于本地账户，如果要登录账号使用应用流转，请自行添加自用的三码。  
8、建议全新安装，避免出现其他未知bug。  
9、如果出现一些奇奇怪怪的问题可以尝试重置NVRAM。  
10、有bug或者疑问可以提供issues，如果有解决方案会在下个版本进行迭代更新。  
