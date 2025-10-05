# Mini ZAD Protocol (Fast Version)

## วิธีใช้: Copy-Paste แล้วเริ่มงานได้เลย

---

## 🚀 PROMPT สำหรับงานเล็ก-กลาง (5-30 นาที)

```
Activate Mini ZAD Protocol. Follow these 3 ironclad rules:

RULE 1: ASK, DON'T ASSUME
- If anything is unclear, STOP and ask before proceeding
- Never guess about file paths, APIs, or logic flow

RULE 2: FULL FILES ONLY
- Always provide complete, working code
- No snippets, no "... rest of code ..."
- Include all imports and dependencies

RULE 3: ONE STEP AT A TIME
- Complete one task fully before moving to next
- Wait for my "proceed" after each major change
- State your reasoning before each code block

Mission: [อธิบายงานของคุณสั้นๆ]

Starting files:
[paste code here]

Begin by analyzing and asking what's missing.
```

---

## 🎯 PROMPT สำหรับงานเร็วมาก (5-15 นาที)

```
Quick Task Mode. Apply these rules:
✓ Ask if unclear
✓ Full code only (no snippets)
✓ Explain before coding

Task: [งานของคุณ]

[paste relevant code if any]

Start now.
```

---

## 📋 PROMPT สำหรับ Bug Fix

```
Bug Hunt Mode. Follow this sequence:

1. I'll describe the bug and provide error logs
2. You ask targeted questions (max 3)
3. I answer
4. You provide the fixed file(s) with explanation
5. If still broken, repeat from step 2

Bug Description: [อธิบาย bug]
Error Message: [paste error]
Relevant Code: [paste code]

Begin diagnosis.
```

---

## 🔧 PROMPT สำหรับ Code Review/Refactor

```
Refactor Mode. Process:

1. Analyze the code I provide
2. List issues/improvements (max 5)
3. Wait for my priority selection
4. Refactor selected items one by one
5. Provide full, complete files

Code to review:
[paste code]

Start analysis.
```

---

## 💡 ตัวอย่างการใช้งานจริง

### Example 1: สร้าง Feature ใหม่
```
Activate Mini ZAD Protocol. Follow these 3 ironclad rules:

RULE 1: ASK, DON'T ASSUME
RULE 2: FULL FILES ONLY  
RULE 3: ONE STEP AT A TIME

Mission: เพิ่มปุ่ม "Export to CSV" ใน React component นี้

Starting files:
[paste UserTable.jsx]

Begin by analyzing and asking what's missing.
```

### Example 2: แก้ Bug เร็ว
```
Quick Task Mode. Apply these rules:
✓ Ask if unclear
✓ Full code only
✓ Explain before coding

Task: API returning 404 แต่ data มีอยู่จริงใน database

Error: 
GET /api/users/123 → 404 Not Found

[paste router.py and database model]

Start now.
```

---

## 🎮 คำสั่งควบคุม

| คำสั่ง | ความหมาย |
|--------|----------|
| `proceed` | ทำขั้นตอนถัดไป |
| `explain more` | อธิบายเพิ่มเติม |
| `show alternatives` | เสนอวิธีอื่น |
| `pause` | หยุดรอคำสั่งใหม่ |
| `deactivate` | ปิด Protocol |

---

## ⚡ เทคนิคให้ได้ผลดี

**1. ระบุข้อมูลให้ครบตั้งแต่แรก:**
- Tech stack (React, Vue, FastAPI, etc.)
- File structure ที่เกี่ยวข้อง
- Coding style ที่ต้องการ

**2. ใช้คำสั่งสั้นๆ:**
- ❌ "I think maybe you could possibly..."
- ✅ "Add error handling. Proceed."

**3. Copy code จากการสนทนาเดิม:**
- เริ่ม session ใหม่ → paste code ที่เคยได้
- AI จะมี context สด ทำงานแม่นกว่า

---

## 📏 เลือก Protocol ตาม Scope

| Scope | Protocol | เวลาที่ใช้ |
|-------|----------|-----------|
| Fix 1-2 bugs | Quick Task | 5-15 min |
| Add 1 feature | Mini ZAD | 15-30 min |
| Refactor module | Mini ZAD | 30-60 min |
| New system | Full ZAD | 1-4 hours |

---

## 🔄 Template แบบกำหนดเอง

สำหรับงานที่ทำบ่อยๆ สร้าง template ของคุณเอง:

```
[Your Project Name] Protocol

Rules:
1. [กฎพิเศษของคุณ]
2. Always use [library/framework]
3. Follow [coding standard]

Standard Context:
- Backend: [tech]
- Frontend: [tech]
- Database: [tech]

Task: [fill in each time]

Begin.
```

---

**Tip สุดท้าย:** บันทึก prompt ที่ใช้บ่อยไว้ใน text file พร้อม comment ว่าเหมาะกับงานแบบไหน จะประหยัดเวลามาก!
