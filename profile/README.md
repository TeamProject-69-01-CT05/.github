<div align="center">
 
# GitDiwaa
 
### เกมเพื่อการเรียนรู้คำสั่ง Git และการทำงานเป็นทีม
 
#### A Game-Based Learning Platform for Git Commands and Team Collaboration
 
**เล่นให้สนุก เรียนรู้ให้เคลียร์ จบเกมปุ๊บ ใช้ Git เป็นปั๊บ**
 
เรียนรู้ตั้งแต่คำสั่งพื้นฐาน ไปจนถึง Branch, Pull Request, Code Review และการทำงานร่วมกันเป็นทีม  
ผ่าน Terminal ที่ใช้ Git จริงในพื้นที่ฝึก ภารกิจที่ตรวจจากสถานะ Repository และโลก Pixel Art ภาษาไทย
 
![Status](https://img.shields.io/badge/status-in%20development-7c3aed?style=for-the-badge)
![Language](https://img.shields.io/badge/language-Thai-22c55e?style=for-the-badge)
 
</div>

---
 
## เรื่องราวภายในเกม
 
เมื่อ **คัมภีร์เวทต้นกำเนิด** ซึ่งเก็บรักษาความรู้เวทมนตร์ทั้งหมดแตกออกเป็น 15 ชิ้น สมดุลของอาณาจักรจึงเริ่มสั่นคลอน
 
ผู้เล่นรับบทเป็น **“เวล”** นักเวทฝึกหัดที่ต้องออกสำรวจหอคอยลึกลับ เก็บรวบรวมเศษคัมภีร์ 11 ชิ้น และเรียนรู้ว่าชิ้นส่วนอีก 4 ชิ้นถูกเก็บไว้ใน **คลังเวทกลาง** การเดินทางช่วงสุดท้ายจึงไม่อาจสำเร็จได้ด้วยตัวคนเดียว—เวลต้องเรียนรู้กฎของสภาจอมเวท ทำงานร่วมกับผู้อื่น ส่งผลงานให้ตรวจสอบ และรวมการเปลี่ยนแปลงอย่างถูกต้อง
 
ทุกภารกิจในโลกเวทมนตร์เชื่อมโยงกับแนวคิดของ Git เพื่อพาผู้เล่นจากการเริ่มต้นใช้งาน ไปสู่การแก้ปัญหาในสถานการณ์ที่ใกล้เคียงการทำงานจริง
 
## เส้นทางการเรียนรู้
 
| ช่วง | ด่าน | สิ่งที่ผู้เล่นได้เรียนรู้ |
| --- | ---: | --- |
| **Act I — The First Fragments** | 1–15 | ตั้งค่า Git, สร้าง Repository, Stage, Commit, ตรวจประวัติ, Branch, Merge และ Remote Workflow |
| **Act II — The Central Archive** | 16–20 | GitHub Flow, Feature Branch, Pull Request, Code Review, การแก้ไขตาม Feedback และ Merge |
| **Act III — The Final Trial** | 21–40 | วิเคราะห์และแก้ปัญหา Git จากสถานการณ์จริง โดยลดคำแนะนำและให้ผู้เล่นตัดสินใจด้วยตนเอง |
 
## จุดเด่นของระบบ
 
- **Real Git Sandbox** — พิมพ์คำสั่ง Git จริงในพื้นที่ฝึกที่แยกไว้สำหรับแต่ละภารกิจ พร้อม Remote Repository จำลองแบบ GitHub
- **Repository-State Validation** — ตรวจผลลัพธ์จากสถานะของ Repository ไม่บังคับให้ผู้เล่นจำคำตอบเพียงรูปแบบเดียว
- **Interactive Terminal & Git Graph** — พิมพ์คำสั่ง ดูผลลัพธ์ และติดตาม Commit และ Branch แบบเห็นภาพ
- **Team Workflow Simulation** — ฝึกสร้าง Pull Request, Review Code, แก้ไขตามความคิดเห็น และจัดการ Merge Conflict
- **40 Story-driven Levels** — 3 Act จากบทเรียนพื้นฐานสู่โจทย์แก้ปัญหา
- **Progression System** — Score, ดาว, Stack, Coin, Rank, Shop และ Weekly Leaderboard
- **Guided Learning** — เป้าหมายย่อย คำใบ้ 3 ระดับ Feedback และบทสรุปเชื่อมโลกเกมกับ Git ในงานจริง
- **Thai Pixel-art Experience** — UI ภาษาไทย ตัวละคร ฉาก และไอเทมในธีมหอคอยเวทมนตร์
## กระบวนการเรียนรู้ในหนึ่งภารกิจ
 
```text
Story & Objective
        ↓
Git Terminal (real Git, sandboxed)
        ↓
Repository State Changes
        ↓
Mission Validation & Feedback
        ↓
Score · Stars · Coins · Progress
```
 
ผู้เล่นมีอิสระในการเลือกคำสั่ง ตราบใดที่สามารถทำให้ Repository ไปถึงสถานะเป้าหมายได้ ระบบจะอธิบายข้อผิดพลาดและผลกระทบของแต่ละการกระทำ เพื่อให้เกิดความเข้าใจมากกว่าการท่องจำ
 
## โครงการในองค์กร
 
- **Git Engine** — แกนระบบจำลองคำสั่งและสถานะ Git
- **Online Server** — ASP.NET Core API สำหรับบัญชีผู้เล่นและ Weekly Leaderboard (Render + Neon PostgreSQL)
- **GitDiwaa Frontend** — พื้นที่พัฒนาส่วนติดต่อผู้เล่นของเกม
## เป้าหมายของโครงการ
 
โครงงานนี้จัดทำขึ้นเพื่อศึกษา ออกแบบ สร้าง และประเมินเกมเพื่อการเรียนรู้คำสั่ง Git และกระบวนการทำงานร่วมกัน โดยประยุกต์แนวคิด **Game-Based Learning** ให้ผู้เรียนได้ทดลอง ลงมือแก้ปัญหา และเห็นผลของคำสั่งในสภาพแวดล้อมที่ปลอดภัย
 
---
 
<div align="center">

 ### Learn Git. Restore the grimoire. Shape your own path.
 
**TeamProject-69-01-CT05 · Academic Year 2569**
 
</div>
 
