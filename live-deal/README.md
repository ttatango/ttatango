# بوابة الإقلاع: صفحة Live Deal

صفحة هبوط لبث العروض المباشر على فيسبوك (فخامة البراء / onlinersv.com).

## التعديل
كل الإعدادات في أعلى `<script>` داخل `index.html` تحت `CONFIG`:
- `liveDate`: موعد البث
- `whatsapp`: رقم واتساب الحجز بالصيغة الدولية (مثال: `9665XXXXXXXX`)
- `facebook`: رابط صفحة فيسبوك
- `depositAmount` و `depositDays`: العربون ومدة إكمال الدفع

نموذج التسجيل يفتح واتساب برسالة جاهزة فيها بيانات العميل، فما يحتاج سيرفر.

## النشر على GitHub Pages
Settings ← Pages ← Source: `Deploy from a branch`، واختاروا الفرع والمجلد الجذر `/`.
بعدها تصير الصفحة على: `https://ttatango.github.io/ttatango/live-deal/`
