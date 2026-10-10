# Thyroid Care

แอปคำแนะนำการปฏิบัติตัวผู้ป่วยผ่าตัดต่อมไทรอยด์ รพ.รามาธิบดี
ติดตั้งลงหน้าจอโฮมได้ และเปิดดูได้โดยไม่ใช้อินเทอร์เน็ต หลังจากเปิดครั้งแรกตอนมีเน็ต

## วิธีขึ้น GitHub Pages
1. สร้าง repository ใหม่ (Public) แล้วอัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (index.html, manifest.json, sw.js, thyroid-icon-180.png, thyroid-icon-192.png, thyroid-icon-512.png)
2. Settings → Pages → Branch: main / (root) → Save
3. รอ 1–2 นาที จะได้ลิงก์ https://<ชื่อบัญชี>.github.io/<ชื่อ repo>/

## เมื่อแก้ไขเนื้อหา
แก้ index.html แล้วเปลี่ยนเลขใน sw.js บรรทัด VERSION (เช่น v1 → v2) ทุกครั้ง
ผู้ป่วยจะได้เวอร์ชันใหม่เมื่อเปิดแอปตอนมีเน็ต
