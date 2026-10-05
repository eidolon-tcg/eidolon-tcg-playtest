# Eidolon TCG Play test

โปรแกรมเล่นทดสอบการ์ดเกม **Eidolon TCG** สำหรับ Windows — จัดเด็ค · เล่นบนกระดาน · เปิดจอคู่แข่งแยกสำหรับสตรีม / เล่นออนไลน์

## ⬇️ ดาวน์โหลด

**[ดาวน์โหลดเวอร์ชันล่าสุด →](https://github.com/eidolon-tcg/eidolon-tcg-playtest/releases/latest)**

ในหน้า Release ให้กดไฟล์ **`Eidolon.TCG.Play.test.Setup.x.y.z.exe`** (ไฟล์ `latest.yml` และ `.blockmap` ใช้สำหรับระบบอัปเดต ไม่ต้องโหลด)

## 💻 ความต้องการของเครื่อง

- Windows 10 / 11 (64-bit)
- พื้นที่ว่างประมาณ 600 MB
- อินเทอร์เน็ต — ใช้ตอนเข้าระบบด้วย PIN ครั้งแรก และตอนตรวจอัปเดต (หลังจากนั้นเล่นออฟไลน์ได้)

## 🛠️ วิธีติดตั้ง

1. เปิดไฟล์ `Setup.exe` ที่โหลดมา
2. ถ้า Windows ขึ้น **"Windows protected your PC"** ให้กด **More info → Run anyway**
   (โปรแกรมยังไม่ได้เซ็นใบรับรอง จึงขึ้นคำเตือนนี้ได้ — ดาวน์โหลดจากหน้านี้เท่านั้น)
3. เลือกโฟลเดอร์ติดตั้ง → Install → เปิดจาก Shortcut บน Desktop

## 🔑 การเข้าเล่น (PIN)

ต้องใส่ **PIN** ที่ได้รับจากทีมงานในหน้า Launcher ถึงจะเข้าเล่นได้
- ระบบจำ PIN ไว้ 30 วัน และต่ออายุให้เองทุกครั้งที่เปิดโปรแกรมแบบออนไลน์
- PIN เป็นของแต่ละคน **ห้ามแชร์** — PIN ที่หลุดจะถูกยกเลิก
- ยังไม่มี PIN / PIN ใช้ไม่ได้ → ติดต่อทีมงาน Eidolon TCG

## 🔄 การอัปเดต

โปรแกรม **ตรวจและโหลดเวอร์ชันใหม่ให้อัตโนมัติ** ตอนเปิดหน้า Launcher
เมื่อโหลดเสร็จจะมีปุ่มให้กด **รีสตาร์ทเพื่ออัปเดต** — ไม่ต้องโหลดไฟล์ติดตั้งใหม่เอง
(ถ้าอัปเดตไม่ขึ้น ให้โหลด `Setup.exe` ล่าสุดจากหน้า Release มาติดตั้งทับได้ — ข้อมูลไม่หาย)

## 💾 ข้อมูลของคุณ

เด็ค การตั้งค่า เกมที่เล่นค้าง และภาพ Sleeve / Playmat ที่อัปโหลด เก็บอยู่ที่
`%APPDATA%\Eidolon TCG Play test\`
- อัปเดต / ติดตั้งทับ → ข้อมูลยังอยู่
- ย้ายเครื่อง → ใช้ปุ่ม **Export** ในหน้า "เด็คของฉัน" แล้ว **Import** ที่เครื่องใหม่

## ❓ แก้ปัญหาเบื้องต้น

| อาการ | วิธีแก้ |
|---|---|
| ขึ้น "Windows protected your PC" | More info → Run anyway |
| ใส่ PIN แล้วเข้าไม่ได้ | ตรวจอินเทอร์เน็ต · PIN อาจหมดอายุหรือถูกยกเลิก → ติดต่อทีมงาน |
| ไม่เห็นการ์ดเทส | การ์ดเทสเห็นเฉพาะ PIN ของผู้ทดสอบ (CBT) ตามสิทธิ์ที่ได้รับ |
| อัปเดตค้าง / ผิดพลาด | ปิดโปรแกรม → โหลด `Setup.exe` ล่าสุดมาติดตั้งทับ |

> repo นี้ใช้เผยแพร่ไฟล์ติดตั้งเท่านั้น ไม่มีซอร์สโค้ด

## License

Copyright (c) 2026 **SAMUNTEAM Co.** All rights reserved.

- โปรแกรมนี้ใช้ได้เฉพาะเพื่อเล่นทดสอบ Eidolon TCG — ห้ามคัดลอก ดัดแปลง เผยแพร่ซ้ำ sublicense
  reverse engineer (รวมถึงแตกไฟล์ app.asar) หรือแฮ็ก/หลบเลี่ยงระบบ PIN อัปเดต และลายน้ำ
- ชื่อเกม กติกา ชื่อการ์ด ข้อความความสามารถ และภาพของระบบ เป็นของ SAMUNTEAM Co.
- การ์ดเทส / CBT เป็นข้อมูลลับที่ยังไม่เปิดตัว ห้ามนำไปเผยแพร่
- ภาพบนการ์ดเทสบางใบอาจเป็นภาพทั่วไปจากภายนอกที่ใช้แทนชั่วคราวเพื่อทดสอบภายใน ลิขสิทธิ์เป็นของเจ้าของภาพ
  SAMUNTEAM Co. ไม่อ้างสิทธิ์และไม่รับผิดชอบต่อการนำไปใช้ภายนอก — เจ้าของภาพแจ้งลบได้
- โปรแกรมให้ใช้ "ตามสภาพ" ไม่มีการรับประกันใดๆ

Eidolon TCG Play test is proprietary software. Copyright (c) 2026 SAMUNTEAM Co. All rights reserved.
It may not be copied, modified, distributed, sublicensed, reverse engineered or tampered with
without prior written permission. Some test-card images may be third-party placeholders used for
internal playtesting only; they remain the property of their respective owners.
