# מפת כאבים (pain-map)

אפליקציה חיה: https://shaharprod.github.io/pain-map/

קוראת את תוצאות הסריקה של [Leads Radar](https://shaharprod.github.io/leads-radar/) מאותו דפדפן (localStorage `lr_results`, **לקריאה בלבד**),
מקבצת ביקורות גוגל שליליות לנושאי כאב, ומציגה לכל כאב מה אפשר להציע לעסקים.

- לא נוגעת בקוד של Leads Radar ולא כותבת למפתחות `lr_*`.
- ביקורות שמושלמות כאן נשמרות רק במפתח `pm_reviews`.
- מפתחות Google Maps ו-Gemini נקראים מההגדרות של Leads Radar באותו דפדפן — לא נשמרים בקוד.
- מצב גיבוי: ייבוא קובץ JSON שיוצא מ-Leads Radar.

V1.00 · 27.9.2026
