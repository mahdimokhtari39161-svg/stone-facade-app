اپلیکیشن موبایل طراحی نمای سنگ خورشید نو

انتشار با GitHub Pages:
1) وارد https://github.com شوید و یک حساب بسازید/وارد شوید.
2) روی New repository بزنید. نام مخزن را stone-facade-app بگذارید و Public را انتخاب کنید.
3) فایل ZIP را Extract کنید. محتوای پوشه stone-facade-mobile را (خود فایل‌ها و پوشه icons، نه پوشه والد) در مخزن بارگذاری کنید.
4) در صفحه مخزن: Add file > Upload files؛ همه فایل‌ها و پوشه icons را بکشید داخل صفحه و Commit changes بزنید.
5) Settings > Pages > Build and deployment: گزینه Deploy from a branch؛ Branch=main و Folder=/(root)؛ Save.
6) پس از چند دقیقه لینک https://USERNAME.github.io/stone-facade-app/ ساخته می‌شود. USERNAME را با نام کاربری GitHub عوض کنید.

نصب روی اندروید: لینک را با Chrome باز کنید > منوی سه‌نقطه > Install app یا Add to Home screen.
نصب روی آیفون: لینک را با Safari باز کنید > Share > Add to Home Screen.

نکات مهم:
- برای نصب PWA باید سایت با HTTPS منتشر شود؛ GitHub Pages این مورد را فراهم می‌کند.
- فایل فعلی برای اجرای سه‌بعدی به اینترنت و بارگیری کتابخانه Three.js از CDN نیاز دارد. پس از بارگیری اولیه، پوسته سایت و منابع CDN در صورت امکان کش می‌شوند؛ عملکرد کاملاً آفلاین تضمین‌شده نیست.
- ذخیره‌های فعلی در حافظه مرورگر همان گوشی هستند و خودکار بین گوشی‌ها/مشتریان همگام نمی‌شوند.
- ارسال سفارش واقعی و هوش مصنوعی آنلاین به بک‌اند/API نیاز دارند؛ تنظیم آدرس API در پنل مدیریت به‌تنهایی سرور ایجاد نمی‌کند.
