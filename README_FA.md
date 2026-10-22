<p align="center">
  <img src="https://raw.githubusercontent.com/Alizjahan/FAntigravity-App-RTL-Persian-Arabic/main/header2.jpg" alt="FAntigravity App Banner" width="100%">
</p>

# مستندات FAntigravity-App-RTL-Persian-Arabic

ابزار **FAntigravity-App-RTL-Persian-Arabic** جهت افزودن قابلیت‌های پیشرفته راست‌به‌چپ (RTL)، شخصی‌سازی تایپوگرافی فارسی و عربی و مدیریت تم به صورت اختصاصی برای نرم‌افزار مستقل **Google Antigravity Standalone Desktop (Electron)** توسعه یافته است.

[English Documentation](./README.md) | [راهنمای فارسی](./README_FA.md) | [الدليل العربي](./README_AR.md)

---

> [!NOTE]
> **اطلاعیه رسمی در خصوص نسخه‌های برنامه:**  
> این افزونه منحصراً برای محیط **Antigravity App** توسعه داده شده است.  
> برای نرم‌افزار **Antigravity IDE** اکستنشن رسمی دیگری نوشته‌ام که می‌توانید مستقیماً در بخش اکستنشن‌ها سرچ کنید و آن را نصب کنید.  
> جهت راهنمایی بیشتر به ریپازیتوری آن مراجعه فرمایید:  
> 🔗 [**FAntigravity-IDE-RTL-Persian-Arabic**](https://github.com/Alizjahan/FAntigravity-IDE-RTL-Persian-Arabic)

---

<div align="center">

### 📸 نمای پنل تنظیمات ۳ زبانه (فارسی | عربی | انگلیسی)

| پنل فارسی | پنل عربی | پنل انگلیسی |
| :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/Alizjahan/FAntigravity-App-RTL-Persian-Arabic/main/assets/preview_fa.png" alt="پنل فارسی FAntigravity App" width="100%" /> | <img src="https://raw.githubusercontent.com/Alizjahan/FAntigravity-App-RTL-Persian-Arabic/main/assets/preview_ar.png" alt="پنل عربی FAntigravity App" width="100%" /> | <img src="https://raw.githubusercontent.com/Alizjahan/FAntigravity-App-RTL-Persian-Arabic/main/assets/preview_en.png" alt="پنل انگلیسی FAntigravity App" width="100%" /> |

</div>

---

## ✨ قابلیت‌ها

- **رابط کاربری ۳ زبانه (فارسی | عربی | انگلیسی)**:
  - دکمه تغییر زبان آنی در هدر پنل کاربری برای جابجایی بین فارسی، عربی و انگلیسی.
- **۳ فونت تعبیه‌شده آفلاین (Offline Fonts)**:
  - **فونت دبی (Dubai Font)**: فونت مدرن، چشم‌نواز و استاندارد برای متون فارسی و عربی.
  - **فونت متغیر وزیرمتن (Vazirmatn Variable)**: فونت دقیق و کلاسیک تعبیه‌شده.
  - **فونت اسنپ وب (Snapp Web)**: فونت وب محبوب برای چیدمان روان.
  - **پشتیبانی از فونت‌های دلخواه سیستم**: امکان استفاده از هر فونت نصب‌شده روی ویندوز یا مک (ایران‌یکان، بی نازنین، ساحل، امیری، قاهره...).
- **سیستم سه‌حالته انتخاب تم**:
  - تم روشن (Light Mode)
  - تم تاریک (Dark Mode)
  - تم ستاره آنتی‌گرویتی (Antigravity Star Mode) با طیف رنگی نئونی
- **حفظ ۱۰۰ درصدی کدهای برنامه‌نویسی و ترمینال**: بلوک‌های `<pre>`، `<code>` و ترمینال همیشه چپ‌چین و دست‌نخورده باقی می‌مانند.
- **تنظیم فونت مستقل برای کلمات انگلیسی و بلوک‌های کد**.
- **گزینه راست‌چین اجباری (Force RTL)** برای هدایت کامل متون حتی با شروع انگلیسی.
- **تنظیم اندازه قلم و فاصله بین خطوط** با دکمه بازنشانی به مقادیر پیش‌فرض.
- **عملکرد کاملاً آفلاین** بدون ارسال داده یا وابستگی به شبکه خارجی.
- **اصلاح خودکار کلید Shift + 2** برای درج علامت @ در صفحه‌کلید فارسی.
- **پشتیبان‌گیری خودکار از فایل اصلی (.bak)** پیش از اعمال هرگونه تغییر.

---

## 🚀 روش‌های نصب و راه‌اندازی

### روش اول: اجرای مستقیم از طریق NPX (پیشنهادی)

در محیط خط فرمان (PowerShell در ویندوز یا Terminal در مک و لینوکس):

```bash
npx -y -p github:Alizjahan/FAntigravity-App-RTL-Persian-Arabic fantigravity
```

> [!TIP]
> **نکته بسیار راحت برای کاربران مک (macOS):**
> اگر از مک استفاده می‌کنید، نیازی به کار با ترمینال ندارید! کافیست داخل چت برنامه Antigravity به هوش مصنوعی بگویید:
> > *"لطفاً FAntigravity رو از ریپازیتوری `github:Alizjahan/FAntigravity-App-RTL-Persian-Arabic` برای من نصب کن"*
> 
> خود ایجنت تمام مراحل نصب، پچ و فعال‌سازی راست‌چین را به صورت خودکار و بدون دردسر برای شما انجام می‌دهد.

### روش دوم: بازگردانی به نسخه اولیه (Restore)

جهت لغو تغییرات و بازگردانی فایل اصلی برنامه با استفاده از فایل پشتیبان:

```bash
npx -y -p github:Alizjahan/FAntigravity-App-RTL-Persian-Arabic fantigravity --restore
```

---

## ⌨️ کلیدهای میانبر

- کلیدهای **`Alt + R`**: سوئیچ آنی راست‌چین و چپ‌چین در کل برنامه.
- کلیک روی آیکون FAntigravity در بالای صفحه: باز شدن پنل تنظیمات تایپوگرافی، تم و زبان.

---

## 👨‍💻 توسعه‌دهنده

توسعه‌یافته توسط **Aliz ([@Alizjahan](https://github.com/Alizjahan))**
- گیت‌هاب: [https://github.com/Alizjahan](https://github.com/Alizjahan)
- تلگرام: [https://t.me/Alizjahan](https://t.me/Alizjahan)

---

## 📄 مجوز

این پروژه تحت مجوز [MIT License](LICENSE) منتشر شده است.
