# 🧠 JaiDee — Adaptive Mental Health Self-Assessment

เว็บประเมินสุขภาพจิตแบบ **interactive + adaptive**
ที่ออกแบบให้เข้าใจง่าย ใช้เวลาไม่นาน และเคารพความเป็นส่วนตัวของผู้ใช้

🔗 Live Demo: https://dizconnectz.github.io/mental-health/

---

## ✨ Overview

JaiDee เป็น web application สำหรับประเมินสุขภาพจิตเบื้องต้น
โดยใช้แนวคิด **adaptive questionnaire (ถามเท่าที่จำเป็น)**
เพื่อลดความรู้สึกเหมือนทำแบบฟอร์มยาว ๆ และเพิ่มคุณภาพของผลลัพธ์

ระบบจะเลือกคำถามถัดไปตามคำตอบของผู้ใช้แบบ real-time
ทำให้ประสบการณ์ใช้งานเป็นธรรมชาติและไม่กดดัน

---

## 🚀 Key Features

* 🧠 **Adaptive Question Flow**
  คำถามจะเปลี่ยนตามคำตอบ (ไม่ถามเกินจำเป็น)

* 📊 **Evidence-based Screening**
  อ้างอิงแบบประเมิน:

  * ST-5 (Stress)
  * 2Q (Depression screening)
  * 9Q / PHQ-9
  * 8Q (Suicide risk)

* ⚡ **Instant Result (Client-side Processing)**
  ประมวลผลทันที ไม่ต้อง reload หรือรอ server

* 🌐 **Multi-language Support**
  รองรับทั้งภาษาไทยและอังกฤษ

* 🔒 **Privacy-first Design**

  * ไม่มีการเก็บข้อมูลผู้ใช้
  * ไม่มี backend / database
  * ทุกอย่างทำงานบน browser

* 🎨 **User-centric UX**

  * UI แบบ conversational
  * ใช้ emoji + visual feedback
  * ลด cognitive load ของผู้ใช้

---

## 🧠 How It Works

1. เริ่มจากการประเมินภาพรวม (ST-5)
2. หากพบความเสี่ยง → ระบบจะ:

   * ถามเพิ่มด้วย 2Q / 9Q
   * ประเมินเชิงลึกมากขึ้น
3. หากมีสัญญาณสำคัญ → ใช้ 8Q เพื่อตรวจสอบความปลอดภัย
4. แสดงผลลัพธ์พร้อมคำแนะนำที่เหมาะสม

> ระบบใช้แนวคิด **progressive disclosure + decision tree logic**

---

## 🏗 Architecture

* **Frontend:** Vanilla HTML / CSS / JavaScript
* **Rendering:** Dynamic UI via JavaScript (SPA-style)
* **State Management:** In-memory (no persistence)
* **Logic:** Rule-based decision tree

---

## 🔧 Tech Stack

* HTML5
* CSS3 (custom design system + animation)
* Vanilla JavaScript (no framework)
* GitHub Pages (deployment)

---

## 🔒 Privacy & Ethics

โปรเจกต์นี้ออกแบบโดยยึดหลัก:

* ❌ ไม่เก็บข้อมูลส่วนตัว
* ❌ ไม่มี tracking / analytics
* ✅ ทำงานทั้งหมดบน client-side
* ✅ เคารพความเป็นส่วนตัวของผู้ใช้ 100%

---

## ⚠️ Disclaimer

เครื่องมือนี้เป็นเพียง **การคัดกรองเบื้องต้น (screening tool)**
ไม่สามารถใช้แทนการวินิจฉัยโดยแพทย์หรือผู้เชี่ยวชาญได้

หากคุณหรือคนใกล้ตัวมีอาการรุนแรง
แนะนำให้ติดต่อผู้เชี่ยวชาญหรือสายด่วนสุขภาพจิต

📞 สายด่วนสุขภาพจิต (ประเทศไทย): 1323 (24 ชั่วโมง)

---

## 💡 Design Philosophy

* **Less friction, more honesty**
  ลดความรู้สึก “กำลังถูกประเมิน”

* **Adaptive over static**
  ถามเท่าที่จำเป็น เพื่อความแม่นยำและ UX ที่ดีขึ้น

* **Human-centered**
  ใช้ภาษาที่ไม่ตัดสิน และเข้าใจผู้ใช้

---

## 🛠 Future Improvements

* เพิ่ม scoring transparency
* เพิ่ม visualization (graph / trend)
* รองรับ PWA / offline mode
* เพิ่ม personalization (optional, privacy-safe)
* เพิ่ม clinical validation layer

---

## 📄 License

MIT License

---

## 🙌 Author

Made with 💜 by Takuma
