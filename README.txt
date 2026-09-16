Nabta Rewards — Real Authentication
هذه نسخة خادم حقيقية: التسجيل وكلمات المرور تُحفظ في SQLite على الخادم، وكلمات المرور تُخزن بعد التشفير بواسطة bcrypt، والجلسة في HttpOnly cookie.

التشغيل:
1) ثبّت Node.js 18+.
2) انسخ .env.example إلى .env واضبط JWT_SECRET و ADMIN_USERNAME و ADMIN_PASSWORD.
3) شغّل: npm install
4) ثم: npm start
5) افتح http://localhost:3000

مهم: لا تستخدم كلمة مرور المشرف الافتراضية في الإنتاج، ولا ترفع ملف .env إلى GitHub.
هذه النسخة لا تنفذ أموالاً حقيقية أو تحويل USDT؛ نظام النقاط والاستبدال تجريبي.
