Drivers:
    HfsPlus: Apple 固件中专有 HFS 文件系统驱动程序
        - https://github.com/acidanthera/OcBinaryData/blob/master/Drivers/HfsPlus.efi
    OpenCanopy: 用于实现图形引导界面
    OpenRuntime: 用作修补 boot.efi 以修复 NVRAM 和更好的内存管理
    ResetNvramEntry: 允许在启动选取器重置 NVRAM

Kexts:
    Lilu: 在 macOS 中执行内核扩展、库和程序修补。
        - https://github.com/acidanthera/Lilu/releases
        - 1.6.7
    VirtualSMC: 模拟 Apple 的 SMC
        - SMCBatteryManager: 测量笔记本电脑上的电池读数
        - https://github.com/acidanthera/VirtualSMC
        - 1.3.2
    SMCAMDProcessor: 监控 AMD CPU 的温度
        - AMDRyzenCPUPowerManagement: AMD CPU 电源管理
        - https://github.com/trulyspinach/SMCAMDProcessor
        - 0.7.1
    RadeonSensor: 显示系统中 AMD GPU 的温度的 Lilu 插件
        - SMCRadeonGPU: 将传感器值导出到 VirtualSMC
        - https://github.com/ChefKissInc/RadeonSensor
        - 1.3.0
    NootedRed: 适用于 AMD Vega iGPU 的 Lilu 插件
        - https://github.com/ChefKissInc/NootedRed
        - #1068
    AppleALC: 适用于非官方支持的编解码器的原生 macOS HD 音频
        - https://github.com/acidanthera/AppleALC
        - 1.8.8
    AirportItlwm: 提供了某些 Airport 功能的面向 macOS 的开源 Intel Wi-Fi 驱动
        - https://github.com/OpenIntelWireless/itlwm
        - 2.3.0-alpha
    IntelBluetoothFirmware: 适用于 macOS 的英特尔蓝牙内核扩展
        - IntelBTPatcher: 修复补丁
        - https://github.com/OpenIntelWireless/IntelBluetoothFirmware
        - 2.3.0
    BlueToolFixup: 蓝牙修复补丁
        - https://github.com/acidanthera/BrcmPatchRAM
        - 2.6.8
    USBPorts: 订制 USB 端口
    VoodooI2C: 适用于 macOS 的英特尔 I2C 控制器和从设备驱动程序
        - https://github.com/VoodooI2C/VoodooI2C
        - 2.8
    NVMeFix: 用于 Apple NVMe 存储驱动程序 IONVMeFamily 的补丁，提高与非 Apple SSD 的兼容性
        - https://github.com/acidanthera/NVMeFix
        - 1.1.1
    AppleMCEReporterDisabler: 关闭 AppleIntelMCEReporter，避免在AMD CPU的设备上报错
        - https://chefkissinc.github.io/Extras/Kexts/AppleMCEReporterDisabler.zip
    RestrictEvents: Lilu 内核扩展，阻止导致不同硬件上出现兼容性问题的不需要的进程
        - https://github.com/acidanthera/RestrictEvents
        - 1.1.3
    ECEnabler: 允许 macOS 读取长度超过 8 位的 EC 字段（电池读取）
        - https://github.com/1Revenger1/ECEnabler
        - 1.0.4
    BrightnessKeys: 提供对 ACPI 亮度更改的支持（键盘的FN键）
        - https://github.com/acidanthera/BrightnessKeys
        - 1.0.3
    HoRNDIS: 适用于 Mac OS X 的 Android USB 网络共享驱动程序
        - https://github.com/TomHeaven/HoRNDIS
        - 9.3