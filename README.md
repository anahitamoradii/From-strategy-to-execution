[README.en.md](https://github.com/user-attachments/files/31248005/README.en.md)
# Dashboard: From Strategy to Execution

English | [فارسی](README.md)

A single-file, fully offline dashboard for managing branding and marketing projects — from business profile to campaign execution.

🔗 [View demo](https://throbbing-cloud-1261.anahita-moradi7.workers.dev/)

## What the project is

A standalone (single-file) HTML dashboard for brand and marketing consultants. It has no server, no database, and no build process; the entire app runs from a single `index.html` file and opens directly in the user's own browser (Chrome/Safari).

Its structure is multi-client: you can create a separate profile for each client/project and switch between them without the data getting mixed up.

## What problem it solves

The data for a branding project — business profile, goals, business model canvas, market research, audience personas, competitor analysis, brand strategy and identity, content calendar, KPIs, finances, and more — is usually scattered across spreadsheets, documents, and disconnected tools. This dashboard brings more than 40 related sections together under a single structure, with JSON export/import for backup and moving data between devices — with no dependency on any cloud service.

## Technology used

- Pure **HTML / CSS / JavaScript** — no framework, no build step
- Browser **localStorage** for complete, client-side, offline data storage
- **Vazirmatn** font (Google Fonts) and **Tabler Icons**, self-hosted/base64-embedded (no external requests for icons)
- Full **RTL** support for Persian

## Running locally

Just open the `index.html` file directly in Chrome or Safari.

> ⚠️ Opening the file from inside Telegram/WhatsApp or a file-manager app disables access to `localStorage`, so no data will be saved after a page refresh.

## Deploying on GitHub Pages

This project is static, so enabling GitHub Pages on this same `index.html` is enough:

1. Go to **Settings → Pages**
2. Under **Source**, select your branch and the root path (`/root`)
3. After a few minutes, the site will be live at something like `https://<username>.github.io/<repo>/`

Replace the demo link at the top of this file with your own repo's actual address.

## A note about the data

All data is stored only in the browser of that same device. To move between devices or back up your data, use the **"Export all data (JSON)"** button inside the app.

## License

Not yet specified — add a `LICENSE` file to the repo to make the terms of use clear.

<div dir="rtl">

# داشبورد از استراتژی تا اجرا

[English](README.en.md) | فارسی

داشبورد تک‌فایلی و کاملاً آفلاین برای مدیریت پروژه‌های برندسازی و بازاریابی — از پروفایل کسب‌وکار تا اجرای کمپین.

🔗 [مشاهده دمو](https://throbbing-cloud-1261.anahita-moradi7.workers.dev/)

## پروژه چیست

یک داشبورد HTML مستقل (single-file) برای مشاوران برند و بازاریابی است. هیچ سرور، دیتابیس یا فرآیند build ندارد؛ کل برنامه در یک فایل `index.html` اجرا می‌شود و روی مرورگر خود کاربر (Chrome/Safari) باز می‌شود.

ساختار آن «چندمشتری» (Multi-client) است: می‌توانی برای هر مشتری/پروژه یک پروفایل جدا بسازی و بین آن‌ها جابه‌جا شوی، بدون این‌که داده‌ها با هم قاطی شوند.

## چه مشکلی حل می‌کند

داده‌های یک پروژه‌ی برندینگ — پروفایل کسب‌وکار، اهداف، بیزینس مدل کانواس، تحقیقات بازار، پرسونای مخاطب، تحلیل رقبا، استراتژی و هویت برند، تقویم محتوا، KPI، مالی و... — معمولاً بین فایل‌های اکسل، اسناد و ابزارهای پراکنده تکه‌تکه می‌شود. این داشبورد بیش از ۴۰ بخش مرتبط را زیر یک ساختار واحد جمع می‌کند و امکان خروجی/ورودی JSON برای پشتیبان‌گیری و انتقال داده بین دستگاه‌ها را می‌دهد — بدون وابستگی به هیچ سرویس ابری.

## تکنولوژی استفاده‌شده

- **HTML / CSS / JavaScript** خالص — بدون فریم‌ورک، بدون build step
- **localStorage** مرورگر برای ذخیره‌سازی کامل داده‌ها (سمت کلاینت، آفلاین)
- فونت **Vazirmatn** (Google Fonts) و **Tabler Icons** به‌صورت self-hosted/base64 (بدون درخواست بیرونی برای آیکون‌ها)
- پشتیبانی کامل **RTL** برای فارسی

## اجرای محلی

فقط فایل `index.html` را مستقیماً در Chrome یا Safari باز کن.

> ⚠️ باز کردن فایل از داخل تلگرام/واتساپ یا اپ فایل‌منیجر، دسترسی به localStorage را غیرفعال می‌کند و در نتیجه هیچ داده‌ای بعد از رفرش صفحه ذخیره نمی‌ماند.

## اجرا روی GitHub Pages

این پروژه استاتیک است، پس فعال‌سازی GitHub Pages روی همین `index.html` کافی‌ست:

1. برو به **Settings → Pages**
2. زیر **Source**، شاخه (branch) و مسیر ریشه (`/root`) را انتخاب کن
3. بعد از چند دقیقه، سایت روی آدرسی مثل `https://<username>.github.io/<repo>/` بالا می‌آید

لینک دمو در بالای همین فایل را با آدرس واقعی ریپوی خودت جایگزین کن.

## نکته درباره‌ی داده‌ها

همه‌ی داده‌ها فقط در مرورگر همان دستگاه ذخیره می‌شوند. برای جابه‌جایی بین دستگاه‌ها یا پشتیبان‌گیری، از دکمه‌ی «خروجی گرفتن از همه داده‌ها (JSON)» داخل برنامه استفاده کن.

## لایسنس

هنوز مشخص نشده — یک فایل `LICENSE` به ریپو اضافه کن تا شرایط استفاده روشن باشد.

</div>
