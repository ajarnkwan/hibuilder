# 🚀 Hi, Builder — Launch Checklist

อัพเดต: พฤษภาคม 2026

---

## ✅ ส่วนที่ AI ทำเสร็จแล้ว

- ✅ บทเรียน 1 — 7 Steps พร้อมเรียน (interactive ทำงานครบ)
- ✅ Landing page ปรับ tone เป็น Early Builder
- ✅ Roadmap 8 บท (บท 1 = "พร้อม", บท 2-8 = "co-create")
- ✅ Glossary 16 คำ + tooltip ทุก Step
- ✅ About page
- ✅ Privacy & Terms page
- ✅ 404 page
- ✅ OG meta tags ทุกหน้า (preview เวลาแชร์ลิงก์)
- ✅ Mobile-friendly responsive design
- ✅ localStorage save (Asset Map + URL แรก)

---

## 🔴 BLOCKER — ต้องทำก่อน launch

### 1. Discord Server Setup

- [ ] **สร้าง Discord server** ชื่อ "Ajarn Kwan" 
- [ ] สร้าง **Hi, Builder sub-category** มี channels:
  - `#welcome` — ที่โพสต์ Day 1 + DM bot
  - `#บทเรียน-1-สนทนา` — คนถามตอบ
  - `#showcase-builder` — โชว์ของที่ทำเสร็จ
  - `#bug-feedback` — แจ้ง bug + suggest
- [ ] **สร้าง bot** สำหรับ DM unique code per บทเรียน
  - แนะนำ: ใช้ MEE6 / Carl-bot / custom Discord.js bot
  - logic: detect post ใน #welcome → DM code 6-digit เฉพาะ user นั้น
- [ ] ทดสอบ bot กับ test account
- [ ] **สร้าง Discord invite link** (permanent)
- [ ] แทนที่ `[ Discord invite link ]` ในไฟล์ทั้งหมด:
  - `Hi-Builder_landing.html`
  - `Hi-Builder_step-1-1.html`
  - `Hi-Builder_about.html`
  - `Hi-Builder_404.html`
  - `Hi-Builder_Discord-Guide.md`

### 2. Line OA

- [ ] **สร้าง Line Official Account** "Ajarn Kwan"
- [ ] ตั้ง welcome message + auto-reply
- [ ] **เก็บ Line OA link / QR code**
- [ ] แทนที่ `[ Line OA link ]` ในไฟล์ทั้งหมด

### 3. รูปอาจารย์ขวัญ

- [ ] **เลือกรูปโปรไฟล์** (recommend 800×800px, square)
- [ ] อัพโหลดเข้า repo เว็บ (เช่น `assets/ajarn-portrait.jpg`)
- [ ] แทนที่ `[ รูปอาจารย์ขวัญ ]` ใน:
  - `Hi-Builder_landing.html` (section #about)
  - `Hi-Builder_about.html`

### 4. Screenshots ใน Discord-Guide

ใน `Hi-Builder_Discord-Guide.md` มี 6 placeholder screenshots — capture และแทนที่:

- [ ] Screenshot 1: หน้า Discord download
- [ ] Screenshot 2: หน้า login Discord
- [ ] Screenshot 3: หน้า join server
- [ ] Screenshot 4: หน้า welcome ใน server
- [ ] Screenshot 5: หน้าโพสต์ใน #welcome
- [ ] Screenshot 6: ตัวอย่าง DM จาก bot

### 5. ทดสอบ End-to-End บน Mobile

- [ ] ทดสอบ **iPhone Safari** — Step 1.1 → 1.7 ทุกขั้น
- [ ] ทดสอบ **Android Chrome** — เหมือนกัน
- [ ] เช็ค: 
  - Quiz ตอบได้
  - Glossary tooltip โผล่ + tap-to-show ทำงาน (mobile)
  - Asset Map กรอกได้ + บันทึกได้
  - Step 1.6 Playground ลองได้
  - Copy buttons ใน Step 1.7 ทำงาน

---

## 🟡 NICE TO HAVE — ทำได้หลัง launch

### 6. Analytics

- [ ] สมัคร **Plausible** หรือ **Google Analytics 4**
- [ ] เพิ่ม tracking script ทุกหน้า
- [ ] ดู: drop-off rate ที่แต่ละ Step

### 7. OG Image (preview เวลาแชร์ลิงก์)

- [ ] ออกแบบ OG image 1200×630px (อาจสร้างใน Canva/Figma)
- [ ] อัพโหลด: `assets/og-image.jpg`
- [ ] เพิ่ม `<meta property="og:image" content="...">` ทุกหน้า

### 8. Custom Domain (optional)

- [ ] ถ้าต้องการ — ซื้อ domain เช่น `hibuilder.ajarnkwan.com`
- [ ] ตั้ง CNAME ใน GitHub Pages
- [ ] รออัพเดต DNS

---

## 📦 รายการไฟล์ทั้งหมดที่จะ deploy

### HTML Pages (13)

| # | ไฟล์ | คำอธิบาย |
|---|---|---|
| 1 | `Hi-Builder_landing.html` | Landing (เริ่มต้น) |
| 2 | `Hi-Builder_botreuan-1.html` | บทเรียน 1 overview |
| 3 | `Hi-Builder_step-1-1.html` | Day 1: สวัสดี |
| 4 | `Hi-Builder_step-1-2.html` | โลก Tech + Quiz 3 ข้อ |
| 5 | `Hi-Builder_step-1-3.html` | Tour AI 5 ตัว + Quiz 3 ข้อ |
| 6 | `Hi-Builder_step-1-4.html` | สมัคร GitHub |
| 7 | `Hi-Builder_step-1-5.html` | Asset Mind Map ⭐ |
| 8 | `Hi-Builder_step-1-6.html` | โครงสร้างเว็บ |
| 9 | `Hi-Builder_step-1-7.html` | สร้าง URL แรก ⭐ peak |
| 10 | `Hi-Builder_glossary.html` | Glossary 16 คำ |
| 11 | `Hi-Builder_about.html` | เกี่ยวกับ |
| 12 | `Hi-Builder_privacy.html` | Privacy & Terms |
| 13 | `Hi-Builder_404.html` | 404 |

### Reference (2)

- `Hi-Builder_v2.md` — Master brief
- `Hi-Builder_Discord-Guide.md` — Discord setup guide

---

## 🚀 Deploy Strategy

### Option A: GitHub Pages (แนะนำ)

1. สร้าง repo `hi-builder` (public) ใน GitHub ของอาจารย์
2. Rename ไฟล์ landing → `index.html` (หน้าแรก default)
3. อัพไฟล์ทั้งหมด + commit
4. Settings → Pages → Source: main / root → Save
5. รอ 1-2 นาที — เว็บ live ที่ `ajarnkwan.github.io/hi-builder/`

**ข้อดี:** ฟรี · ไว ·match กับสิ่งที่สอนใน Step 1.7 (eat your own dog food)

### Option B: Vercel / Netlify

ถ้าต้องการ custom domain หรือ analytics built-in

---

## 📢 Launch Announcement

### Posts ที่ควรทำในวัน launch

#### Facebook (เน้น context + invitation)

```
🌱 Hi, Builder บทเรียน 1 พร้อมแล้ว

อาจารย์ตั้งใจสร้างคอร์สสอน "การสร้างของในยุค AI" สำหรับคนเริ่มจาก 0
จบ 8 บทเรียน คุณจะมีเว็บ + แอปบนมือถือที่แก้ปัญหาในชีวิตจริง

ตอนนี้บทเรียน 1 พร้อมเรียน — ใช้ AI สร้าง URL แรกของคุณเองใน 2 ชั่วโมง

เป็น Early Builder รุ่นแรก — feedback ของคุณจะ shape บทถัดไป

🔗 [URL ของเว็บ]
💸 ฟรี ไม่มีโฆษณา
```

#### TikTok (สั้น 30 วิ)

```
hook: "ใครคิดว่า AI จะแย่งงานเรา?"
turn: "หรือเราจะใช้ AI สร้างของเอง?"
proof: เปิดเว็บ → กรอก asset → ได้ URL จริง
CTA: "ลิงก์ใน bio · ฟรี · เริ่มจาก 0"
```

#### Line OA broadcast

```
[ส่งหา subscribers]
🌱 Hi, Builder บทเรียน 1 พร้อมแล้ว
อาจารย์อยากให้คุณเป็น Early Builder รุ่นแรก

→ [link]
```

---

## 📊 Metrics to Track (สัปดาห์ 1)

| Metric | Target สัปดาห์ 1 |
|---|---|
| ผู้เข้า landing page | 100+ |
| ผู้เริ่มบทเรียน 1 | 30+ |
| ผู้จบ Step 1.7 (ได้ URL) | 5+ |
| Discord member | 20+ |
| Feedback ที่ได้ (qualitative) | 5+ คน |

---

## 💡 สิ่งที่ต้องระวัง

- **Discord bot จะเป็น single-point-of-failure** — ถ้าผิดพลาด ผู้เรียนผ่าน Step 1.1 ไม่ได้ → เตรียม fallback (manual code distribution)
- **GitHub Pages free tier** มี soft limit (100 GB bandwidth/month) — ไม่น่าเกินสำหรับการเริ่มต้น
- **AI tool quotas เปลี่ยนตลอด** — Step 1.3 บอก "ม.ค. 2026" อาจต้องอัพเดต quarterly

---

## ❓ ใครต้องช่วย?

- **Discord bot setup** — ถ้าทำเองยาก หา dev เพื่อนช่วย ~1-2 ชม.
- **รูปประกอบ + screenshots** — ใช้เวลาเอง 2-3 ชม.
- **Mobile testing** — ใช้เครื่องของอาจารย์ + เพื่อน 2-3 คน

---

**Total estimated time: 1-2 สัปดาห์** ก่อน launch

ขอให้สนุกกับการ launch! 🚀
