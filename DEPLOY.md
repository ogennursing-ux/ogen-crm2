# 🚀 העלאה לאוויר — עוגן CRM

הפרויקט מוכן לפרסום (git repo מאותחל עם commit). שתי דרכים לכתובת חיה **חדשה** — אף אחת מהן **לא** נוגעת ב‑`ogen-crm1` הקיים.

---

## ⚡ דרך A — Netlify Drop (הכי מהיר, ~30 שניות, בלי חשבון)
1. פותחים **https://app.netlify.com/drop**
2. גוררים את התיקייה **`C:\Users\WIN-11-26\Desktop\ogen-crm`** אל תוך העמוד
3. מקבלים מיד כתובת ציבורית (למשל `some-name.netlify.app`). זהו.

> זו בדיוק השיטה שמומלצת במסמך האב. מצוין לקבל כתובת חיה להשוואה מול המערכת הקיימת.

---

## 🐙 דרך B — GitHub repo חדש (תואם ל‑setup הקיים; GitHub Desktop מותקן)
התיקייה כבר repo עם commit נקי, אז זה מהיר:
1. **GitHub Desktop** → `File → Add Local Repository` → בוחרים `C:\Users\WIN-11-26\Desktop\ogen-crm`
2. **Publish repository** → שם: **`ogen-crm2`** (⚠️ לא `ogen-crm1`) → Public → Publish
3. ב‑GitHub: **Settings → Pages → Source: `main` / root → Save**
4. חי תוך ~5–10 דק׳ בכתובת `https://ogennursing-ux.github.io/ogen-crm2`

---

## הערות
- קוד גישה: `1234` (משתנה בהגדרות).
- קישור ראיון: הוסיפו `?mode=interview` לכתובת.
- Firebase/AI: נקודות‑חיבור בלבד בגרסה זו (ברירת מחדל = מקומי). לפני שהופכים את זה למחליף אמיתי — יש לחבר Firebase ו‑Gemini כפי שקיים ב‑`ogen-crm1`.
