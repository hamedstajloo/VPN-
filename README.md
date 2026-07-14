# 📊 پنل کاربری شیک و مدرن 3X-UI (Sanaei)

یک فرانت‌اند مدرن، زیبا و بهینه برای نمایش وضعیت مصرف، زمان باقی‌مانده و حجم کانفیگ‌های کاربران در پنل 3X-UI.

<p align="center">
  <img src="preview.png" alt="پیش‌نمایش پروژه" width="100%">
</p>

---

## ✨ ویژگی‌ها

- 📱 طراحی کاملاً واکنش‌گرا (Responsive)
- ⏱️ نمایش روزهای باقی‌مانده از اعتبار سرویس
- 📊 نمایش میزان مصرف حجم، آپلود و دانلود
- 🌐 پشتیبانی از چند سرور و نمایش پینگ (Latency)
- 📥 دانلود مستقیم برنامه
- 📋 کپی آسان لینک اتصال
- 📷 نمایش QR Code
- ⚡ رابط کاربری مدرن، روان و بهینه

---

## 🚀 نصب خودکار

دستور زیر را در ترمینال سرور اجرا کنید:

```bash
curl -fsSL https://raw.githubusercontent.com/hamedstajloo/sanaei-user-panel/main/index.html -o /etc/x-ui/index.html
```

یا در صورت نیاز با دسترسی روت:

```bash
sudo curl -fsSL https://raw.githubusercontent.com/hamedstajloo/sanaei-user-panel/main/index.html -o /etc/x-ui/index.html
```

---

## ⚙️ فعال‌سازی در 3X-UI

1. وارد پنل **3X-UI** شوید.
2. به بخش **Subscription Settings** بروید.
3. در قسمت **Custom Path** مسیر زیر را وارد کنید:

```text
/etc/x-ui/
```

4. تنظیمات را ذخیره کنید.
5. در صورت نیاز سرویس را ریستارت کنید:

```bash
systemctl restart x-ui
```

---

## 📁 ساختار پروژه

```text
sanaei-user-panel/
├── index.html
├── preview.png
├── README.md
└── LICENSE
```

---

## 📸 پیش‌نمایش

تصویر زیر نمایی از رابط کاربری پروژه را نمایش می‌دهد.

<p align="center">
  <img src="preview.png" alt="Screenshot" width="100%">
</p>

---

## 🤝 مشارکت

در صورت تمایل می‌توانید پیشنهادات و Pull Requestهای خود را ارسال کنید تا پروژه بهتر شود.

---

## 📄 License

This project is licensed under the MIT License.
