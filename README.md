# Catalina 10.15.5 (19F101)
# ASUS-B150-PRO-GAMING-Hackintosh-EFI OpenCore 0.58

 - 配置清单: 
   - Intel(R) Core(TM) i7-6700 CPU @ 3.40GHz
   - Kingston 8G DDR4 2666 * 2
   - SAPPHIRE AMD Radeon RX 480
   - Teclast SATA 240G A850
   - ViewSonic VX2478-4K-HD * 2 


- BIOS需要打开选项
  - VT-x
  - Above 4G decoding
  - Hyper-Threading
  - Execute Disable Bit
  - EHCI/XHCI Hand-off
  - OS type: Windows 8.1/10 UEFI Mode
  - DVMT Pre-Allocated(iGPU Memory): 64MB


- BIOS建议要关闭的选项
  - Fast Boot
  - Secure Boot
  - VT-D （可以不关闭）
  - CSM
  - Thunderbolt
  - Intel SGX
  - Intel Platform Trust
  - CFG Lock



- 参考网站：
    - OpenCore: https://dortania.github.io/OpenCore-Desktop-Guide/config.plist/coffee-lake.html
    - ProperTree：https://github.com/corpnewt/ProperTree
    - GenSMBIOS：https://github.com/corpnewt/GenSMBIOS

## 使用了一个月，目前使用未发现问题
### 如何你使用了这EFI作为安装，那建议你把：ShowPicker 设置为true，否则你将会看不到启动菜单
