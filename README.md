# KeyRush-Webapp
KeyRush — ระบบฝึกพิมพ์คำสั่ง (Interactive Terminal Training)
KeyRush เป็นเว็บแอปพลิเคชันสำหรับฝึกใช้งานคำสั่ง Command Line ของระบบปฏิบัติการ Linux และ Windows ผ่านรูปแบบเกมภารกิจ ผู้ใช้สามารถเลือกด่าน ฝึกพิมพ์คำสั่งใน Terminal จำลอง (xterm.js) พร้อมเห็นภาพจำลองผลของคำสั่งแบบเรียลไทม์ เก็บ EXP เพิ่ม Level ดูสถิติการเล่นย้อนหลังผ่านปฏิทิน และแข่งขันคะแนนผ่าน Leaderboard ได้

โปรเจกต์นี้แบ่งออกเป็น 2 repository หลัก ได้แก่

keyrush-frontend — ส่วนหน้าเว็บ พัฒนาด้วย Next.js, React, TypeScript และ Tailwind CSS
keyrush-backend — ส่วน API Server พัฒนาด้วย Hono, Cloudflare Workers, TypeScript, Prisma และ Cloudflare D1 (SQLite)
