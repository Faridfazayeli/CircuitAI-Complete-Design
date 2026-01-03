# 🛠️ سیستم تعمیرکار هوشمند (CircuitAI)

<div align="center">
  
![GitHub](https://img.shields.io/badge/توسعه‌دهنده-faridfazayeli-blue)
![License](https://img.shields.io/badge/مجوز-MIT-green)
![Status](https://img.shields.io/badge/وضعیت-طراحی%20کامل-purple)

</div>

## 📖 معرفی
**سیستم تعمیرکار هوشمند (CircuitAI)** یک پلتفرم کامل برای تعمیرات الکترونیکی مبتنی بر هوش مصنوعی است. این سیستم به تعمیرکاران کمک می‌کند تا با استفاده از تکنولوژی‌های پیشرفته، تعمیرات را سریع‌تر و دقیق‌تر انجام دهند.

## ✨ ویژگی‌های اصلی

### 🤖 هوش مصنوعی و پردازش تصویر
- تشخیص خودکار قطعات روی بردهای الکترونیکی
- OCR تخصصی برای خواندن نوشته‌های روی برد
- تحلیل خودکار عیوب و ارائه راه‌حل

### 📱 رابط کاربری پیشرفته
- اپلیکیشن موبایل با دوربین تخصصی
- پنل مدیریت تحت وب
- نمایش نقشه‌های شماتیک تعاملی

### 🛠️ راهنمای تعمیر هوشمند
- مراحل قدم‌به‌قدم تعمیر
- ویدئوهای آموزشی
- لیست ابزارهای مورد نیاز
- هشدارهای ایمنی

### 💰 سیستم کسب درآمد
- اشتراک‌های دسته‌بندی شده
- پرداخت آنلاین با درگاه‌های ایرانی
- مدیریت کاربران و تعمیرات

## 🏗️ معماری سیستم

### لایه‌های معماری
1. **لایه نمایش**: اپ موبایل (React Native)
2. **لایه کسب و کار**: میکروسرویس‌های Node.js
3. **لایه هوش مصنوعی**: سرویس‌های Python
4. **لایه داده**: PostgreSQL، MongoDB، Redis
5. **لایه ذخیره‌سازی**: MinIO برای تصاویر

### میکروسرویس‌ها
- **سرویس احراز هویت**: مدیریت کاربران و مجوزها
- **سرویس تعمیرات**: مدیریت جلسات تعمیر
- **سرویس نقشه‌ها**: مدیریت نقشه‌های شماتیک
- **سرویس پرداخت**: مدیریت تراکنش‌ها مالی
- **سرویس هوش مصنوعی**: پردازش تصویر و OCR

## 📁 ساختار پروژه

\\\
CircuitAI-Complete-Design/
├── 📁 docs/                    # مستندات
│   ├── 📁 fa/                 # مستندات فارسی
│   │   └── طراحی-کامل-سیستم.md
│   └── 📁 en/                 # مستندات انگلیسی
├── 📁 src/                    # سورس کد
│   ├── 📁 backend/           # بک‌اند (Node.js + Express)
│   ├── 📁 frontend/          # فرانت‌اند (React)
│   ├── 📁 mobile/            # اپ موبایل (React Native)
│   └── 📁 ai/                # هوش مصنوعی (Python)
├── 📁 docker/                # کانفیگ‌های داکر
├── 📁 database/              # اسکریپت‌های دیتابیس
├── 📁 tests/                 # تست‌های پروژه
├── 📄 README.md              # این فایل
├── 📄 .gitignore             # فایل‌های نادیده گرفته شده
└── 📄 LICENSE                # مجوز MIT
\\\

## 📱 دستگاه‌های پشتیبانی شده

### دسته‌بندی اصلی
1. **📱 موبایل و تبلت**
   - iPhone (همه مدل‌ها)
   - Samsung Galaxy سری
   - Xiaomi و Redmi
   - Huawei و Honor

2. **💻 لپ‌تاپ و کامپیوتر**
   - MacBook (همه مدل‌ها)
   - Dell XPS و Inspiron
   - HP Pavilion و EliteBook
   - Lenovo ThinkPad و Yoga

3. **🎮 کارت گرافیک**
   - NVIDIA GeForce سری
   - AMD Radeon سری

4. **🖥️ مین‌برد کامپیوتر**
   - Asus ROG و TUF
   - Gigabyte AORUS
   - MSI MPG و MAG

5. **💾 ذخیره‌سازی**
   - HDD (همه برندها)
   - SSD SATA و NVMe
   - درایوهای اکسترنال

6. **🌐 تجهیزات شبکه**
   - مودم ADSL و VDSL
   - روترهای بی‌سیم
   - سوئیچ‌های شبکه

7. **📺 مانیتور و تلویزیون**
   - مانیتورهای LCD و LED
   - تلویزیون‌های هوشمند
   - پنل‌های OLED

## 🚀 شروع توسعه

### پیش‌نیازها
- Node.js 18 یا بالاتر
- Python 3.10 یا بالاتر
- Docker و Docker Compose
- PostgreSQL 15
- MongoDB 6

### نصب و راه‌اندازی
\\\ash
# کلون ریپازیتوری
git clone https://github.com/faridfazayeli/CircuitAI-Complete-Design.git
cd CircuitAI-Complete-Design

# نصب وابستگی‌های بک‌اند
cd src/backend
npm install

# نصب وابستگی‌های فرانت‌اند
cd ../frontend
npm install

# نصب وابستگی‌های هوش مصنوعی
cd ../ai
pip install -r requirements.txt
\\\

### راه‌اندازی با داکر
\\\ash
# ساخت و اجرای کانتینرها
docker-compose up -d

# مشاهده لاگ‌ها
docker-compose logs -f
\\\

## 📊 وضعیت توسعه

### ✅ تکمیل شده
- طراحی کامل معماری سیستم
- طراحی دیتابیس و جداول
- طراحی API‌های اصلی
- طراحی UI/UX همه صفحات
- طراحی سیستم امنیتی
- طراحی سیستم پرداخت

### 🔄 در حال توسعه
- پیاده‌سازی سرویس احراز هویت
- توسعه اپلیکیشن موبایل
- پیاده‌سازی سرویس OCR
- یکپارچه‌سازی درگاه پرداخت

### 📅 برنامه آینده
- افزودن پشتیبانی زبان عربی
- توسعه سیستم آموزش ویدیویی
- ایجاد بازارچه قطعات
- افزودن دستگاه‌های جدید

## 🔧 تکنولوژی‌های استفاده شده

### فرانت‌اند
- **React Native 0.72+** برای اپ موبایل
- **React 18+** برای پنل مدیریت
- **TypeScript** برای type safety
- **Redux Toolkit** برای state management
- **React Navigation 6+** برای navigation
- **Axios** برای API calls

### بک‌اند
- **Node.js 18+** با **Express.js**
- **Socket.io** برای ارتباط real-time
- **JWT** برای احراز هویت
- **bcrypt** برای hash کردن رمزها
- **Sequelize** برای ORM

### دیتابیس
- **PostgreSQL 15+** برای داده‌های ساختاریافته
- **MongoDB 6+** برای داده‌های نیمه‌ساختاریافته
- **Redis 7+** برای کش و session

### هوش مصنوعی
- **TensorFlow 2.12+** برای مدل‌های ML
- **OpenCV 4.8+** برای پردازش تصویر
- **Tesseract.js** برای OCR
- **EasyOCR** برای OCR پیشرفته

### زیرساخت
- **Docker** برای containerization
- **Docker Compose** برای orchestration
- **Nginx** به عنوان reverse proxy
- **GitHub Actions** برای CI/CD

## 📚 مستندات طراحی

برای مشاهده مستندات کامل طراحی سیستم به زبان فارسی، فایل زیر را مطالعه کنید:

[📖 مستندات طراحی کامل فارسی](./docs/fa/طراحی-کامل-سیستم.md)

## 🤝 مشارکت در توسعه

1. ریپازیتوری را Fork کنید
2. Branch جدید ایجاد کنید: \git checkout -b feature/امکانات-جدید\
3. تغییرات خود را Commit کنید: \git commit -m 'اضافه کردن امکانات جدید'\
4. به ریپازیتوری اصلی Push کنید: \git push origin feature/امکانات-جدید\
5. Pull Request ایجاد کنید

## 📄 مجوز

این پروژه تحت مجوز **MIT** منتشر شده است. برای جزئیات بیشتر فایل [LICENSE](./LICENSE) را مطالعه کنید.

\\\
MIT License

Copyright (c) 2026 faridfazayeli

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
\\\

## 👤 اطلاعات توسعه‌دهنده

- **نام**: faridfazayeli
- **ایمیل**: farid.fazayeli@gmail.com
- **GitHub**: https://github.com/faridfazayeli
- **تاریخ ایجاد پروژه**: 2026/01/03
- **آخرین بروزرسانی**: 2026/01/03 03:44

## 📞 تماس

برای اطلاعات بیشتر، پیشنهادات یا گزارش مشکلات با ایمیل زیر تماس بگیرید:  
📧 farid.fazayeli@gmail.com

---

<div align="center">
ساخته شده با ❤️ توسط **faridfazayeli** برای جامعه تعمیرکاران ایران و جهان
</div>

<div align="center">
✨ به امید پیشرفت تکنولوژی و کمک به توسعه مهارت‌های فنی ✨
</div>
