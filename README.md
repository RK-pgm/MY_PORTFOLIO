# เว็บพอร์ตโฟลิโอ
เว็บไซต์พอร์ตโฟลิโอส่วนตัวสำหรับแนะนำตัวและรวบรวมผลงาน ใบประกาศนียบัตร และช่องทางติดต่อ พัฒนาด้วย HTML และ CSS โดยใช้ไลบรารี AOS สำหรับเอฟเฟกต์แอนิเมชันขณะเลื่อนหน้าเว็บ

## หน้าภายในเว็บไซต์

- **Home** — แนะนำตัวบนหน้าแรก
- **About** — ข้อมูลส่วนตัว ความสนใจ และทักษะ
- **Certificate / Portfolio** — แสดงผลงานและใบประกาศนียบัตร
- **Contact** — ช่องทางสำหรับติดต่อ

## ผลงานที่นำเสนอ

- Bangmod Programming Competition
- Basic ROS Robotics
- Edge AI with Edge Impulse
- Engineering Fundamentals Electronics
- Python Programming for AI & Data
- CHULA Project
- HamsterHub
- Idea Canvas
- PSU Project และ PSU Image Project
- KUMOOC, THNCA และ Wisdom

## เทคโนโลยีที่ใช้

- HTML5
- CSS3
- [AOS](https://michalsnik.github.io/aos/) สำหรับเอฟเฟกต์การแสดงผล
- [Font Awesome](https://fontawesome.com/) สำหรับไอคอนในหน้าติดต่อ

## วิธีเปิดเว็บไซต์

1. ดาวน์โหลดหรือโคลนโปรเจกต์นี้
2. เปิดไฟล์ `index.html` ในเว็บเบราว์เซอร์

เว็บไซต์เป็นเว็บแบบ static จึงไม่ต้องติดตั้งแพ็กเกจหรือเปิดเซิร์ฟเวอร์ก่อนใช้งาน โดยไฟล์ CSS รูปภาพ และหน้า HTML ควรอยู่ในโฟลเดอร์เดียวกันตามโครงสร้างปัจจุบัน ทั้งนี้ AOS และ Font Awesome โหลดจาก CDN จึงต้องเชื่อมต่ออินเทอร์เน็ตเพื่อแสดงเอฟเฟกต์และไอคอน

## โครงสร้างไฟล์

```text
.
├── index.html                 # หน้าแรก
├── index2_about.html          # หน้าแนะนำตัว
├── index3_certificate.html    # หน้าผลงานและใบประกาศนียบัตร
├── index4_contac.html         # หน้าติดต่อ
├── index.css                  # สไตล์ของเว็บไซต์
└── *.jpg                      # รูปภาพประกอบผลงานและใบประกาศนียบัตร
```
