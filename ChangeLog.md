# TTRS VRS Changelog

![alt text][logo]

สามารถดาวน์โหลดโปรแกรม TTRS VRS โดยกดที่หมายเลขของเวอร์ชั่น

## [Released] (Last version)

## [1.1.6] - 2021-03-31
### Added
- แก้ปัญหาวางสายคนหูหนวกที่เกิดจาก Audio Stream timeout โดยเพิ่มการเช็ค Video Stream timeout ของสายที่โทรแบบ Video
- แก้ปัญหาการส่งข้อความที่นำหน้าด้วย Space Bar จากโปรแกรม TTRS-VRS ฝั่งล่าม แล้วทำให้โปรแกรม TTRS Video บน Mobile ดับ โดยป้องกันการขึ้นต้นข้อความด้วย Space Bar
- แก้ปัญหาไม่บันทึก Chat Log ในบางครั้ง โดยการเพิ่มเงื่อนไขในการบันทึก Chat Log ตอนจบการสนธนาให้ครบทุกเงื่อนไข

## [1.1.5] - 2021-03-26
### Added
- เพิ่มรูปแบบการโทรออกให้สามารถเลือกโทรแบบ Audio หรือ Video ได้
- เพิ่มรูปแบบการโทรแบบประชุมสาย (Conference) ได้
- เพิ่มรูปแบบการแสดงผลสายปกติที่เป็น Video พร้อมกัน 2 สาย
- เพิ่มรูปแบบการแสดงผล Self view ให้สามารถปรับขนาดการแสดงผลเจ้าหน้าที่ล่ามได้
- เพิ่มปุ่มสำหรับ เปิด-ปิด Self view ได้เพราะในการโทรประชุมสายมีการแสดงผลเจ้าหน้าที่ล่ามในภาพอยู่แล้ว
- ปรับให้ต้อง Login ทุกครั้งที่เปิดโปรแกรม
- เปลี่ยนปุ่มควบคุมแต่ละสายให้สามารถคุมได้จากทุกแท็บ
- สายที่เป็นการโทรแบบประชุมสายจะเปลี่ยนชื่อแท็บเป็นคำว่า “Conference”
- เปลี่ยน icon ปุ่มโทรเข้าแต่ละสาย และปุ่มวางสายทุกสาย
- เปลี่ยน icon ปุ่มโทร แบบประชุมสาย (Conference)

## [1.1.4] - 2021-03-15
### Added
- แก้ไขปัญหาโปรแกรมปิดเกิดจาก UI ใหม่ไม่สามารถวางสาย Miss call ที่เร็วเกิน 1 วินาที เนื่องจากการดึงข้อมูลยังไม่เสร็จ  
- แก้ไขปัญหาอยู่ๆมี popup ขึ้นให้ login ใหม่ แล้วสถานะหลุด เลยต้อง login ใหม่ถึงจะใช้งานได้

## [1.1.3] - 2021-03-12
### Added
- แก้ไขปัญหาโปรแกรมปิดเกิดจาก UI ใหม่ไม่สามารถการรับสายใหม่ขณะที่สายเก่ายังวางสายไม่สมบูรณ์ได้ 
- แก้ไขปัญหาเลือกเบอร์ที่ประวัติ แล้วกดโทรออกอีกรอบไม่ได้

## [1.1.2] - 2021-03-12
### Added
- ปรับปรุง GDB launcher เวอร์ชั่นใหม่ที่สามารถอัพโหลด GDB log ขึ้นเซิร์ฟเวอร์และจะไม่ทำให้โปรแกรมปิดเมื่อ GDB launcher ทำงานผิดปกติ
- แก้ไขปัญหาการโทรออกเวลาช่องหมายเลขโทรออกเป็นช่องเปล่าได้

## [1.1.1] - 2021-03-11
### Added
- แก้ไขปัญหาการแสดงผล Making , VRI, Emergency และ Receiving ที่มีการแสดงใน tab ที่ไม่ถูกต้อง 

## [1.1.0] - 2021-03-08
### Added
- ปรับปรุง UI ใหม่ให้สามารถรองรับการทำงานแบบประชุมสาย (Conference) ได้

## [1.0.14] - 2021-02-26
### Added
- แก้ไขปัญหาโปรแกรมปิดเกิดจากความผิดพลาดในการ Free Memory หลายจุดของ GDB launcher
- แก้ไขปัญหาโปรแกรมปิดเพราะ GDB launcher ทำงานผิดปกติ โดยการนำ GDB launcher ออกจากโปรแกรม

## [1.0.13] - 2021-02-24
### Added
- แก้ไขปัญหาโปรแกรมปิดเมื่อวางสายเพราะ clear memory หลัง update ประวัติการโทรผิดพลาด
- แก้ไขปัญหาโปรแกรมปิดเมื่อได้รับข้อความเข้ามา แต่ข้อความที่ได้รับมีขนาด 0 ตัวอักษร
- แก้ไขปัญหาโปรแกรมปิดเมื่อวางสายเพราะ clear memory หลังการแปลง Decoder ในส่วน Real Time Text (RTT) ผิดพลาด

## [1.0.12] - 2021-02-15
### Added
- แก้ไขปัญหาโปรแกรมปิดเมื่อรับสายเพราะชื่อล่ามยาว
- แก้ไขปัญหาการแสดงผลชื่อผู้ใช้เพี้ยนเพราะการแปลง Encode (UTF8) ชื่อผู้ใช้ภาษาไทยผิด
- แก้ไขปัญหาโปรแกรมปิดเมื่อการแสดงผล Debug Log ผิดพลาด
- แก้ไขปัญหาโปรแกรมปิดเพราะไฟล์ Config ไม่ Update
- เพิ่มฟังก์ชันการอัพโหลด Debug Log พร้อมกับ GDB Log ขึ้นเซิร์ฟเวอร์เมื่อโปรแกรมทำงานผิดพลาด

## [1.0.11] - 2021-01-20
### Added
- เพิ่มรูปแบบการแสดงผล Self view ให้สามารถปรับตำแหน่งแสดงผลเจ้าหน้าที่ล่ามได้
- เพิ่มรูปแบบการแสดงผล Making สีเขียว, VRI สีส้ม, Emergency สีแดง และ Receiving สีชมพู ให้ชัดขึ้น
- เพิ่มการแสดงผลด้วยชื่อหรือเบอร์โทรบนแท็บ In-Call เมื่อโทรออกหรือรับสาย
- เพิ่มส่วนของการปิด-เปิดเสียงฝั่งคนหูหนวกและคนหูดี
- เพิ่มส่วนของการปิด-เปิดไมโครโฟนชองเจ้าหน้าที่ล่าม
- เพิ่มฟังก์ชันการอ่านค่าความผิดพลาดเมื่อโปรแกรมปิดอย่างผิดปกติ โดยใช้ GDB
- เพิ่มฟังก์ชันการอัพโหลด GDB log ขึ้นเซิร์ฟเวอร์เมื่อโปรแกรมทำงานผิดพลาด

## [1.0.10] - 2020-04-22
### Added
- เพิ่มรองรับแสดงชื่อผู้ใช้ภาษาไทย
- แก้ไขการใช้งาน Receiving ในรูปแบบวิดีโอ
- แก้ไขการดีบั๊ก RTT

### TAG
- Commit [089897a](https://bitbucket.org/nectec_vrs/linphone-desktop-3-9-1-rtt/commits/089897a0437abe3fc80a629462233527223d97f2)

## [1.0.9] - 2020-01-16
### Added
- แก้ไขปัญหาโปรแกรมแคลชตอนพิมพ์ (GUI insert RTT error)
- เพิ่มฟังก์ชันเลือกรูปแบบการส่งสถานะข้อความ เช่น @switch

### TAG
- Commit [60be0fd](https://bitbucket.org/nectec_vrs/linphone-desktop-3-9-1-rtt/commits/60be0fdc009b67f0c54eece70d73a8733a3a05af)

## [1.0.8] - 2019-12-22
### Added
- แก้ไขปัญหาโปรแกรมแคลชตอนพิมพ์เร็วๆ
- แก้ไขปัญหาโปรแกรมแคลชหลังจากวางสาย
- ปรับรูปแบบการแสดงวิดีโอ
- เปลี่ยนรูปแบบการเปลี่ยน Self view วิดีโอล่าม
- ปิดการแสดง Logs บางส่วน

### TAG
- Commit [d107bf4](https://bitbucket.org/nectec_vrs/linphone-desktop-3-9-1-rtt/commits/d107bf4bec56584c1cc1685b57e52d150574dd30)

## [1.0.7] - 2019-11-06
### Added
- เพิ่มรูปแบบการแสดงผล VRI
- กำหนด SIP port random เป็นค่าเริ่มต้น
- กำหนด  RTP port range  audio 7078 - 7098, video 9078 - 9098 เป็นค่าเริ่มต้น
- แก้ไขการเรียก VRS API ใหม่
- เพิ่มตัวอย่าง Config file สำหรับ VRS API

### TAG
- Commit [067e055](https://bitbucket.org/nectec_vrs/linphone-desktop-3-9-1-rtt/commits/067e055e8871b6b862447e50be2a2bee13249e17)

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
[1.1.6]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.1.6/TTRS-VRS-V.1.1.6.exe
[1.1.5]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.1.5/TTRS-VRS-V.1.1.5.exe
[1.1.4]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.1.4/TTRS-VRS-V.1.1.4.exe
[1.1.3]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.1.3/TTRS-VRS-V.1.1.3.exe
[1.1.2]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.1.2/TTRS-VRS-V.1.1.2.exe
[1.1.1]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.1.1/TTRS-VRS-V.1.1.1.exe
[1.1.0]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.1.0/TTRS-VRS-V.1.1.0.exe
[1.0.14]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.14/TTRS-VRS-V.1.0.14.exe
[1.0.13]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.13/TTRS-VRS-V.1.0.13-7-g5a37135.exe
[1.0.12]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.12/TTRS-VRS-V.1.0.12.exe
[1.0.11]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.11/TTRS-VRS-V.1.0.11.exe
[1.0.10]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.10/TTRS-VRS-V.1.0.10-1-g089897a.exe
[1.0.9]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.9/TTRS-VRS-V.1.0.9-2-g60be0fd.exe
[1.0.8]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.8/TTRS-VRS-V.1.0.8-1-gd107bf4.exe
[1.0.7]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.7/TTRS-VRS-V.1.0.7-29-g067e055.exe
[1.0.6]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.6/TTRS-VRS-V.1.0.6-28-g3155cb4.exe
[1.0.5]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.5/TTRS-VRS-V.1.0.5-27-gfeec918.exe
[1.0.4]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.4/TTRS-VRS-V.1.0.4-25-g4f123c5.exe
[1.0.3]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.3/TTRS-VRS-V.1.0.3-23-g5deb0f0.exe
[1.0.2]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.2/TTRS-VRS-V.1.0.2-22-g4fb0793.exe
[1.0.1]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/source/1.0.1/TTRS-VRS-V.1.0.1-21-gacd8d5e.exe
[logo]: https://gitlab.spinsoft.co.th/pc/ttrs_vrs_changelog/raw/master/TTRS-VRS.png "Logo TTRS VRS"