# BuxDU Xodimlar Davomati — GitHub Pages

Repository root papkasiga quyidagi 2 faylni joylang:

- `index.html` — dashboard
- `davomat.xlsx` — barcha foydalanuvchilar ko‘radigan joriy Excel

## Yangilash
Yangi davomat kelganda GitHub repository ichidagi `davomat.xlsx` faylini xuddi shu nom bilan almashtiring. `index.html` o‘zgarmaydi. Sahifa har ochilganda `davomat.xlsx` ni serverdan qayta yuklaydi (`cache: no-store`).

## Excel nazorati
Dashboard Excelni ishlatishdan oldin ID, Xodim, Fakultet, Bo‘lim/Kafedra, Lavozim va sana bloklari strukturasini tekshiradi. Mos kelmasa server Excel xatosi ko‘rsatiladi va noto‘g‘ri fayl statistikaga qo‘llanmaydi.

## GitHub Pages
Settings → Pages → Deploy from a branch → `main` / root ni tanlang.

Eslatma: GitHub Pages ommaviy bo‘lsa, `davomat.xlsx` ham ommaga ochiq bo‘lishi mumkin. Real xodimlar davomat ma’lumotlari uchun private/authenticated universitet serveri xavfsizroq.
