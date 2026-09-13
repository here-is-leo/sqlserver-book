# 📋 Changelog

<div align="center">

**All notable changes to the SQL Server Book project will be documented in this file.**

**همه تغییرات مهم پروژه کتاب SQL Server در این فایل ثبت می‌شود.**

</div>

---

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

فرمت بر اساس [Keep a Changelog](https://keepachangelog.com/fa/1.1.0/) است
و این پروژه از [Semantic Versioning](https://semver.org/lang/fa/) پیروی می‌کند.

---

## 📖 Table of Contents / فهرست

- [Unreleased](#-unreleased)
- [1.0.0 — 2026-09-14](#100--2026-09-14)
- [Versioning Guide](#-versioning-guide--راهنمای-نسخهگذاری)
- [Change Categories](#-change-categories--دستهبندی-تغییرات)

---

## 🔮 [Unreleased]

### 🎯 Planned Features — ویژگی‌های برنامه‌ریزی‌شده

#### Added / اضافه خواهد شد
- 🔍 **Full-text search** across all 51 pages — جستجوی متن کامل در تمام صفحات
- 💬 **Comments system** powered by Giscus — سیستم نظرات با Giscus
- 📴 **PWA support** with offline mode — پشتیبانی PWA و حالت آفلاین
- 📄 **PDF export** button for downloading the entire book — دکمه دانلود PDF کتاب
- 🎥 **Video tutorials** embedded per chapter — ویدیوهای آموزشی برای هر فصل
- 🧪 **Interactive quizzes** at the end of each section — آزمون‌های تعاملی
- 💼 **Interview questions bank** for SQL Server jobs — بانک سوالات مصاحبه
- 🌏 **More languages**: Arabic, Turkish, Russian — زبان‌های بیشتر
- 📊 **Reading statistics** dashboard — داشبورد آمار مطالعه
- 🎨 **Custom theme builder** — سازنده پوسته سفارشی

### 🔧 Planned Improvements — بهبودهای برنامه‌ریزی‌شده

#### Changed / تغییر خواهد کرد
- Improve accessibility to full WCAG 2.1 AAA compliance — بهبود دسترس‌پذیری
- Optimize bundle size below 200KB — بهینه‌سازی حجم به زیر ۲۰۰KB
- Enhance mobile navigation UX — بهبود تجربه کاربری موبایل
- Add more code examples with real-world scenarios — مثال‌های بیشتر

#### Fixed / رفع خواهد شد
- Minor RTL alignment issues in code blocks — رفع مشکلات ترازبندی در بلوک‌های کد
- Sidebar scroll position on page change — موقعیت اسکرول سایدبار

---

## 🎉 [1.0.0] — 2026-09-14

### 🌟 Initial Release — انتشار اولیه

اولین نسخه کامل کتاب جامع SQL Server با **۵۱ صفحه محتوای عمیق** منتشر شد.

The first complete release of the SQL Server Book with **51 pages of deep content**.

---

### ✨ Added — اضافه شد

#### 📚 Content / محتوا

- **۵۱ صفحه محتوای آموزشی کامل** درباره SQL Server از مبتدی تا حرفه‌ای
- **۱۲ بخش موضوعی** با ساختار پله‌پله:
  - بخش ۱: مقدمه و مبانی (صفحات ۱-۴)
  - بخش ۲: زبان SQL و SELECT (صفحات ۵-۹)
  - بخش ۳: JOINها و روابط (صفحات ۱۰-۱۳)
  - بخش ۴: زیرکوئری‌ها و CTEها (صفحات ۱۴-۱۶)
  - بخش ۵: DML و مدیریت داده (صفحات ۱۷-۲۰)
  - بخش ۶: DDL و طراحی پایگاه داده (صفحات ۲۱-۲۵)
  - بخش ۷: T-SQL پیشرفته (صفحات ۲۶-۳۰)
  - بخش ۸: تراکنش‌ها و همزمانی (صفحات ۳۱-۳۴)
  - بخش ۹: بهینه‌سازی و کارایی (صفحات ۳۵-۳۹)
  - بخش ۱۰: امنیت (صفحات ۴۰-۴۳)
  - بخش ۱۱: توابع تحلیلی و JSON/XML (صفحات ۴۴-۴۷)
  - بخش ۱۲: سناریوهای عملی و منابع (صفحات ۴۸-۵۱)

#### 🌍 Internationalization / بین‌المللی‌سازی

- **پشتیبانی دوزبانه کامل** (فارسی + انگلیسی)
- **طراحی RTL** برای فارسی و **LTR** برای انگلیسی
- **تعویض زبان با یک کلیک** بدون reload
- **ذخیره‌سازی زبان انتخابی** در `localStorage`
- **فونت‌های مناسب**: Vazirmatn برای فارسی، JetBrains Mono برای کد

#### 🎨 User Interface / رابط کاربری

- **پوسته تاریک و روشن** با تعویض فوری
- **ذخیره‌سازی خودکار پوسته** در `localStorage`
- **طراحی کاملاً واکنش‌گرا** (موبایل، تبلت، دسکتاپ)
- **Sidebar قابل جمع‌شدن** با overlay در موبایل
- **ناوبری با کیبورد** (کلیدهای ← → و ↑ ↓)
- **Transitions نرم** بین صفحات (fadeSlide animation)
- **Highlight سینتکس T-SQL** در بلوک‌های کد
- **نوار پیشرفت مطالعه** در بالای صفحه

#### 📖 Navigation / ناوبری

- **فهرست مطالب تعاملی** با گروه‌بندی موضوعی
- **شماره‌گذاری صفحات** به فارسی و انگلیسی
- **دکمه‌های قبلی/بعدی** برای حرکت بین صفحات
- **هایلایت صفحه جاری** در سایدبار
- **اسکرول خودکار سایدبار** به صفحه فعال
- **پشتیبانی از Deep Linking** با URL hash (`#5`)

#### 🖨️ Print Support / پشتیبانی چاپ

- **استایل چاپ بهینه** برای خروجی PDF
- **پنهان‌سازی عناصر غیرضروری** در چاپ
- **page-break مناسب** برای هر صفحه کتاب
- **رنگ‌های مناسب چاپ** (بدون هدر و فوتر)

#### ♿ Accessibility / دسترس‌پذیری

- **ARIA labels** برای دکمه‌های تعاملی
- **Focus outlines** برای ناوبری کیبورد
- **Semantic HTML5** markup
- **`prefers-reduced-motion` support** برای کاهش انیمیشن
- **`prefers-color-scheme` detection** برای پوسته خودکار

#### 🔧 Technical / فنی

- **تک‌فایل HTML** بدون هیچ dependency
- **بدون build step** — فقط باز کردن در مرورگر
- **حجم کل ~۲۵۰KB** (شامل فونت‌ها)
- **زمان بارگذاری < ۱ ثانیه**
- **Vanilla JavaScript ES6+** بدون framework
- **CSS Custom Properties** برای theming
- **Grid و Flexbox** برای layout
- **بدون Node.js یا npm**

#### 📝 Content Quality / کیفیت محتوا

- **مثال‌های واقعی و قابل اجرا** در هر صفحه
- **سناریوهای پروژه‌محور** (فروش، تحلیل لاگ)
- **جدول‌های مقایسه‌ای** برای مفاهیم کلیدی
- **Info Boxها** برای نکات مهم، هشدارها و موفقیت‌ها
- **چک‌لیست‌های عملی** در انتهای هر فصل
- **تمرین‌های پروژه‌محور** برای یادگیری فعال

#### 🏗️ Project Structure / ساختار پروژه

- **`README.md`** — معرفی کامل و زیبا با انیمیشن
- **`LICENSE`** — مجوز MIT
- **`CHANGELOG.md`** — همین فایل
- **`CONTRIBUTING.md`** — راهنمای مشارکت
- **`.gitignore`** — جلوگیری از commit فایل‌های زائد
- **`.github/ISSUE_TEMPLATE/`** — قالب‌های Issue
- **`.github/PULL_REQUEST_TEMPLATE.md`** — قالب Pull Request

---

### 🎯 Key Highlights — نکات برجسته

| ویژگی | جزئیات |
|-------|--------|
| **تعداد صفحات** | ۵۱ صفحه |
| **تعداد بخش‌ها** | ۱۲ بخش موضوعی |
| **زبان‌ها** | فارسی + انگلیسی |
| **پوسته‌ها** | روشن + تاریک |
| **حجم کل** | ~۲۵۰KB |
| **Dependencies** | صفر |
| **زمان بارگذاری** | < ۱ ثانیه |
| **نمونه‌های کد** | ۱۵۰+ مثال T-SQL |
| **جدول‌های مقایسه** | ۲۵+ جدول |
| **سناریوهای عملی** | ۲ سناریوی کامل |

---

### 🙏 Credits — قدردانی

- **نویسنده:** Leo (Ilya Farahani)
- **الهام‌گرفته از:** Microsoft Learn، Itzik Ben-Gan، SQLskills
- **فونت‌ها:** Vazirmatn، JetBrains Mono
- **Badgeها:** Shields.io
- **میزبانی:** GitHub Pages

---

### 📜 License — مجوز

این پروژه تحت مجوز **MIT** منتشر شده است. برای جزئیات [LICENSE](LICENSE) را ببینید.

Released under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 📌 Versioning Guide — راهنمای نسخه‌گذاری

این پروژه از **Semantic Versioning** (`MAJOR.MINOR.PATCH`) پیروی می‌کند:

| بخش | چه زمانی افزایش می‌یابد |
|-----|------------------------|
| **MAJOR** (مثلاً 1.0.0 → 2.0.0) | تغییرات ناسازگار (Breaking changes) |
| **MINOR** (مثلاً 1.0.0 → 1.1.0) | افزودن ویژگی جدید سازگار |
| **PATCH** (مثلاً 1.0.0 → 1.0.1) | رفع باگ‌های سازگار |

---

## 🏷️ Change Categories — دسته‌بندی تغییرات

از این دسته‌ها برای توضیح تغییرات استفاده می‌شود:

| نشان | دسته | توضیح |
|------|------|-------|
| ✨ | **Added** | ویژگی جدید |
| 🔧 | **Changed** | تغییر در رفتار موجود |
| 🗑️ | **Deprecated** | ویژگی که به‌زودی حذف می‌شود |
| ❌ | **Removed** | ویژگی حذف‌شده |
| 🐛 | **Fixed** | رفع باگ |
| 🔒 | **Security** | اصلاح امنیتی |
| 📝 | **Documentation** | تغییر در مستندات |
| 🎨 | **Style** | تغییر ظاهری (بدون تغییر منطق) |
| ⚡ | **Performance** | بهبود کارایی |

---

## 🔗 Links — لینک‌های مفید

- 🌐 [Live Demo](https://here-is-leo.github.io/sqlserver-book/)
- 📖 [README](README.md)
- 🤝 [Contributing Guide](CONTRIBUTING.md)
- 📜 [License](LICENSE)
- 🐛 [Report a Bug](https://github.com/here-is-leo/sqlserver-book/issues/new?template=bug_report.md)
- 💡 [Request a Feature](https://github.com/here-is-leo/sqlserver-book/issues/new?template=feature_request.md)
- 💬 [Discussions](https://github.com/here-is-leo/sqlserver-book/discussions)

---

## 📅 Version History — تاریخچه نسخه‌ها

| نسخه | تاریخ | توضیح |
|------|-------|-------|
| [1.0.0](#100--2026-09-14) | 2026-09-14 | 🎉 انتشار اولیه |
| [Unreleased](#-unreleased) | — | 🔮 در حال توسعه |

---

<div align="center">

**📖 Read the book online: [here-is-leo.github.io/sqlserver-book](https://here-is-leo.github.io/sqlserver-book/)**

**⭐ If you find this useful, please give it a star!**

<br>

Made with ❤️ by [Leo](https://github.com/here-is-leo)

</div>

---

<!-- ═══════════════════════════════════════════════ -->
<!-- Keep a Changelog Reference:                    -->
<!-- https://keepachangelog.com/en/1.1.0/           -->
<!-- Semantic Versioning Reference:                 -->
<!-- https://semver.org/spec/v2.0.0.html            -->
<!-- ═══════════════════════════════════════════════ -->

[Unreleased]: https://github.com/here-is-leo/sqlserver-book/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/here-is-leo/sqlserver-book/releases/tag/v1.0.0
