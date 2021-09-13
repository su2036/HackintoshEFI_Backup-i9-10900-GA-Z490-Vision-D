# Hackintosh-i9-10900-GA-Z490-Vision-D
![My-Hackintosh](Docs/my-hackintosh-i9-z490_vision-D.png)


## HW
- CPU : Intel i9-10900
- M/B : Gigabyte Z490 Vision D
  - Audio: Realtek ALC1220-VB
  - 1Gbit Ethernet: Intel I219-V
  - 2.5Gbit Ethernet: Intel I225-V
  - Two USB-C/Thunderbolt 3 ports
- RAM : G.Skill Trident Z 3600Mhz XMP 16GB*2
- GPU : Gigabyte Radeon Vaga56 8GB
- WiFi/BT : fenvi T919 BCM9436CD
- CASE : 리안리 PC-O11 Dynamic RAZER
- Monitor : c27jg54 *3 Triple

---

# OpenCore Update

## Step 1. OpenCorePkg Releases Check & Latest release Download
- [OpenCorePkg Github](https://github.com/acidanthera/OpenCorePkg/releases)([https://github.com/acidanthera/OpenCorePkg/releases](https://github.com/acidanthera/OpenCorePkg/releases))

### 업데이트 교체 파일
- OpenCore-0.7.3-RELEASE(다운파일) > X64 >EFI
    - OpenCore-0.7.3-RELEASE 파일 구성 이미지 펼치기
	> i[OC-Release-file](Docs/OC-file.png)

    - ./BOOT/**BOOTx64.efi**
    - ./OC/**OpenCore.efi**
- My EFI Volumes
    - /Volumes/EFI/EFI/BOOT/**BOOTx64.efi**
    - /Volumes/EFI/EFI/OC/**OpenCore.efi**
    - /Volumes/EFI/EFI/OC/Drivers/**(사용중인 Driver 파일 전체)**
    - ~~/Volumes/EFI/EFI/OC/Bootstrap/**Bootstrap.efi~~ (0.7.x 부터 삭제)**

## Step 2. Latest release Kexts Download

- 최신버전의 Lilu, VirtualSMC, WhateverGreen, AppleALC 필수 업데이트

### [Lilu](https://github.com/acidanthera/Lilu/releases)

- Github Release : [https://github.com/acidanthera/Lilu/releases](https://github.com/acidanthera/Lilu/releases)


### [VirtualSMC](https://github.com/acidanthera/VirtualSMC/releases)

- Github Release : [https://github.com/acidanthera/VirtualSMC/releases](https://github.com/acidanthera/VirtualSMC/releases)

### [WhateverGreen](https://github.com/acidanthera/WhateverGreen/releases)

- Github Release : [https://github.com/acidanthera/WhateverGreen/releases](https://github.com/acidanthera/WhateverGreen/releases)


### [AppleALC](https://github.com/acidanthera/AppleALC/releases)

- Github Release : [https://github.com/acidanthera/AppleALC/releases](https://github.com/acidanthera/AppleALC/releases)

