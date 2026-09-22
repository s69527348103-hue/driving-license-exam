# ติวใบขับขี่ — วิธีเอาขึ้นเว็บไซต์ของตัวเอง

โฟลเดอร์นี้คือเว็บไซต์สำเร็จรูป (index.html + audio/) ไม่ต้อง build ไม่ต้องติดตั้งอะไร

## วิธีที่ 1: Netlify (ง่ายสุด ไม่ต้องใช้คำสั่ง)
1. เปิด https://app.netlify.com/drop (สมัครฟรี/ล็อกอินก่อน)
2. ลากไฟล์ `driving-exam-site.zip` หรือลากทั้งโฟลเดอร์ `site` ไปวางบนหน้านั้น
3. รอสักครู่จะได้ลิงก์ เช่น https://ชื่อสุ่ม.netlify.app — เปลี่ยนชื่อได้ที่ Site configuration > Change site name

## วิธีที่ 2: GitHub Pages
1. สร้าง repository ใหม่บน GitHub (ตั้งเป็น Public)
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์ `site` (ลากไฟล์ + โฟลเดอร์ audio ใส่ในหน้า "Add file > Upload files")
3. Settings > Pages > Source: "Deploy from a branch" > Branch: main, โฟลเดอร์ /(root) > Save
4. รอ 1–2 นาที จะได้ลิงก์ https://ชื่อผู้ใช้.github.io/ชื่อrepo/

## หมายเหตุ
- ต้องเก็บ `index.html` และโฟลเดอร์ `audio/` ไว้ด้วยกันเสมอ (ขนาดรวมประมาณ 10 MB)
- ไฟล์เสียงสร้างจากเสียงไทย Premwadee (Microsoft Edge neural TTS) ควรใช้เพื่อการเรียนรู้ส่วนตัว/ไม่แสวงหากำไร
- เนื้อหาข้อสอบมาจากบทความต้นฉบับปี 2018 ตรวจเกณฑ์ล่าสุดกับกรมการขนส่งทางบกก่อนสอบจริง
