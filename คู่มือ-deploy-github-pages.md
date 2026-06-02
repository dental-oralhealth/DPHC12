# 📘 คู่มือ Deploy เว็บประชุม DPHC12 → GitHub Pages

> ทำครั้งเดียว ใช้งานได้ทั้ง PC และมือถือ ฟรี ไม่หมดอายุ

---

## ✅ สิ่งที่ต้องมีก่อน
- บัญชี GitHub (มีอยู่แล้ว ✓)
- ไฟล์ `index.html` (แนบมาในชุดนี้ ✓)

---

## 🚀 ขั้นตอน (ทำบน PC)

### ขั้นตอนที่ 1 — สร้าง Repository ใหม่

1. เปิด [https://github.com/new](https://github.com/new)
2. ตั้งชื่อ Repository เป็น **`dphc12`** (หรือชื่ออื่นก็ได้)
3. ตั้งเป็น **Public** ✓
4. **อย่า** ติ๊ก "Add a README file"
5. กด **Create repository**

---

### ขั้นตอนที่ 2 — อัปโหลดไฟล์

1. ใน Repository ที่เพิ่งสร้าง กด **"uploading an existing file"**  
   _(หรือกด Add file → Upload files)_
2. ลาก **`index.html`** ไปวางในช่องอัปโหลด
3. เลื่อนลงมา กด **Commit changes**

---

### ขั้นตอนที่ 3 — เปิด GitHub Pages

1. กดเมนู **Settings** (ของ Repository นี้)
2. เมนูซ้ายมือ เลือก **Pages**
3. ส่วน **Branch** เลือก **main** → folder **/ (root)**
4. กด **Save**

⏳ รอประมาณ **1–3 นาที** แล้ว refresh หน้า

---

### ขั้นตอนที่ 4 — รับ URL

หลัง deploy สำเร็จ GitHub จะแสดง URL ประมาณนี้:

```
https://<ชื่อบัญชีของคุณ>.github.io/dphc12/
```

ตัวอย่าง: `https://dental-anamai.github.io/dphc12/`

---

## 🔄 การอัปเดตเนื้อหาในอนาคต

1. แก้ไขไฟล์ `index.html` บนเครื่อง
2. ไปที่ Repository → คลิกไฟล์ `index.html`
3. กด ✏️ (Edit) → วางโค้ดใหม่ → Commit changes
4. รอ 1–2 นาที เว็บจะอัปเดตอัตโนมัติ

---

## ⚠️ หมายเหตุเรื่องรูปแบนเนอร์

รูปแบนเนอร์ใช้ Google Drive Thumbnail URL:
```
https://drive.google.com/thumbnail?id=FILE_ID&sz=w1600
```

**เงื่อนไข:** ไฟล์รูปใน Google Drive ต้องตั้งเป็น  
**"Anyone with the link"** → Viewer ✓ (ตั้งไว้แล้ว)

หากรูปไม่ขึ้น → ให้ตรวจสอบ sharing setting ของไฟล์รูปใน Drive อีกครั้ง

---

## 📞 สอบถามเพิ่มเติม

สำนักทันตสาธารณสุข กรมอนามัย  
กลุ่มสนับสนุนวิชาการและการวิจัย
