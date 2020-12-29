# opencore-msi-gaming-x570-gaming-plus

# OpenCore MSI X570 Gaming Plus

OpenCore Files for AMD Board : MSI X570 Gaming Plus - 29.12.2020

BIOS-Version: 7C37vA84 (Beta version) | SMBIOS MacPro7,1

Please generate new SMBIOS for your config.plist: https://github.com/corpnewt/GenSMBIOS

Based on Dortania-Guide : https://dortania.github.io/OpenCore-Desktop-Guide/

Software:

- OpenCore 0.6.4: https://github.com/acidanthera/OpenCorePkg/releases

 - GUI with files (icons etc.) included
 - Used Kexts (up-to-date @ 29.12.2020):
   - AMDRyzenCPUPowerManagement.kext (https://github.com/trulyspinach/SMCAMDProcessor)
   - VirtualSMC.kext (https://github.com/acidanthera/VirtualSMC)
   - SMCAMDProcessor.kext (https://github.com/trulyspinach/SMCAMDProcessor)
   - AppleALC.kext (https://github.com/acidanthera/applealc)
   - AppleMCEReporterDisabler.kext (https://github.com/acidanthera/bugtracker/files/3703498/AppleMCEReporterDisabler.kext.zip)
   - Lilu.kext (https://github.com/acidanthera/Lilu)
   - MacProMemoryNotificationDisabler.kext (https://github.com/IOIIIO/MacProMemoryNotificationDisabler)
   - NVMeFix.kext (https://github.com/acidanthera/NVMeFix)
   - RealtekRTL8111.kext (https://github.com/Mieze/RTL8111_driver_for_OS_X)
   - USBPorts.kext (Custom integrated in repo)
   - WhateverGreen.kext (https://github.com/acidanthera/whatevergreen)
   
- MacOS Catalina 10.15.7 (Upgrade from 10.15.5 worked)


Hardware:

- Motherboard: MSI X570 Gaming Plus (BIOS 7C37vAB | 2020-11-04 ) (https://www.msi.com/Motherboard/support/MPG-X570-GAMING-PLUS)
- NVMe SSD (Samsung EVO)
- Ryzen 5 (17h, 2nd Gen.) 
- AMD GPU (RX570) | First PCI-E slot
- NVIDIA GPU (RTX2070), deactivated by Spoof-SSDT.aml | 2nd PCI-E slot


Used Tools:

OpenCore Configurator : https://mackie100projects.altervista.org/download-clover-configurator/

GenSMBIOS : https://github.com/corpnewt/GenSMBIOS

Proper Tree : https://github.com/CorpNewt/ProperTree

MaciASL : https://sourceforge.net/projects/maciasl/

-------

-- What is not working:

- Sleep (Save Energy)

- 2 x USB 2.0 Ports (Backside)
