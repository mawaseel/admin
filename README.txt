MAWASEEL ADMIN
Domain: https://admin.mawaseel.ps

Separate administration site connected to the same Firebase project.
Admins can add orders, choose the partner, update order status, and manage the order flow.
Non-admin users are redirected to the main partner site.

PRIMARY ADMIN LOGIN
-------------------
The admin login UI now uses a username + password flow.
The password is verified by Firebase Authentication and is intentionally NOT hardcoded in HTML.
See ADMIN_ACCOUNT_SETUP.txt locally for the one-time account setup. Do NOT upload that file publicly.

BACKEND V3
----------
إنشاء وحذف حسابات الأدمن أصبح عبر Backend آمن باستخدام Firebase Admin SDK.
الموقع المحلي يتصل بـ http://127.0.0.1:8787
والإنتاج يتصل بـ https://mawaseel-backend.onrender.com
راجع BACKEND_SETUP.txt ومجلد backend في الحزمة الكاملة.
