# TTRS VRS Changelog

![alt text][logo]

สามารถดาวน์โหลดโปรแกรม TTRS VRS โดยกดที่หมายเลขของเวอร์ชั่น

## [Released] (Last version)

## [1.0.6] - 2019-06-01
### Added
- แก้ URL API เพื่อรองรับ PBX version 2
- แก้ RTP Time เพื่อรองรับ PBX version 2

### TAG
- Commit [3155cb4](https://bitbucket.org/nectec_vrs/linphone-desktop-3-9-1-rtt/commits/3155cb4642bd128da58bbc004ac5404ac7b40b3b)

## [1.0.5] - 2019-04-24
### Added
- ปรับสถานะ DND ให้ชัดเจนขึ้น
- ปรับสถานะ DND ให้ลิงค์กับสถานะ DND ของ Server โดยใช้ SIP Messages
- แก้ไขคำผิด "ว่างสายสนทนา" เป็น "วางสายสนทนา"
- แสดงชื่อล่ามที่เข้าชื่อเข้าใช้งานจากเดิมจะเป็นแสดงหมายเลข
- แสดงประวัติการสนทนาเป็น 200 สายล่าสุด
- ปิดปุ่มกดปิดโปรแกรม
- แก้ไขบั๊กลงชื่อเข้าใช้งานแล้วกดปุ่ม "Close"
- เพิ่ม Debug log
- แก้บั๊กคลิกเลือกประวัติการโทรแสดงหมายเลขผู้ใช้งานผิดพลาด
- แก้บั๊กเลือก DND ขณะมีการใช้งานอยู่

### TAG
- Commit [feec918](https://bitbucket.org/nectec_vrs/linphone-desktop-3-9-1-rtt/commits/feec9188bd4d995967a4ada448f27d4505e6b7ae)

## [1.0.4] - 2018-12-26
### Added
- เพิ่มฟังก์ชันเขียน debug log โดยอัตโนมัติ เก็บในรูปแบบปี, เดือน, วัน

### TAG
- Commit [4f123c5](https://bitbucket.org/nectec_vrs/linphone-desktop-3-9-1-rtt/commits/4f123c590bf0c8fe1ca0c27883d1267f0da474b3?at=vrs-dev-newrtt)

## [1.0.3] - 2018-12-21
### Added
- ปรับ API สำหรับลงชื่อเข้าใช้งานให้สามารถใช้งานได้ทั้ง Username และ Extension
- เพิ่งฟังก์ชันกำหนดค่า API ผ่าน Config ไฟล์ได้

### TAG
- Commit [5deb0f0](https://bitbucket.org/nectec_vrs/linphone-desktop-3-9-1-rtt/commits/5deb0f033fcf3e9b4fcbc926cec5d62a6db49d7d?at=vrs-dev-newrtt)

## [1.0.2] - 2018-10-09
### Added
- เพิ่มปุ่มสำหรับเลือก Online (DND-Off), DND-Short (DND 1), DND-Long (DND 2)
- เพิ่มฟังก์ชันช่องกดหมายเลขสำหรับโทรออกให้สามารถกดได้แค่ 01234567890*# เท่านั้น
- ตัดปุ่ม DialPad ABCD ออก
- เปลี่ยนใช้งานเป็น IP Address
- กำหนดค่าเริ่มต้นของ Codec (ulaw, alaw, gsm h264)

### TAG
- Commit [4fb0793](https://bitbucket.org/nectec_vrs/linphone-desktop-3-9-1-rtt/commits/4fb0793de63b49e49d5cab7337fa096cae5ed71d?at=vrs-dev-newrtt)

## [1.0.1] - 2018-09-18
### Added
- แก้ไขบั๊กเวลาส่งข้อความไม่แสดง
- แก้ไขบั๊ก ttrsvrs_ignoresend_message กรณีไม่ได้ระบุค่า

### TAG
- Commit [acd8d5e](https://bitbucket.org/nectec_vrs/linphone-desktop-3-9-1-rtt/commits/acd8d5e38fd2184db490cd3485edf6ef50e0ebdc?at=vrs-dev-newrtt)

[Released]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/Released/TTRS-VRS-current.zip
[1.0.6]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.6/TTRS-VRS-V.1.0.6-28-g3155cb4.exe
[1.0.5]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.5/TTRS-VRS-V.1.0.5-27-gfeec918.exe
[1.0.4]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.4/TTRS-VRS-V.1.0.4-25-g4f123c5.exe
[1.0.3]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.3/TTRS-VRS-V.1.0.3-23-g5deb0f0.exe
[1.0.2]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.2/TTRS-VRS-V.1.0.2-22-g4fb0793.exe
[1.0.1]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.1/TTRS-VRS-V.1.0.1-21-gacd8d5e.exe
[logo]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/TTRS-VRS.png "Logo TTRS VRS"