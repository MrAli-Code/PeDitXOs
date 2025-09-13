# أدوات PeDitXOS

## اختيار اللغة:

[**English**](README.md) | [**فارسی**](README_fa.md) | [**中文**](README_zh.md) | [**Русский**](README_ru.md) | [**Türkçe**](README_tr.md) | [**العربية**](README_ar.md)

## 🚀 ما هو PeDitXOS؟

**PeDitXOS** هو مجموعة من البرامج النصية التي تحول جهاز OpenWrt الخاص بك إلى بوابة شبكة قوية وحديثة وسهلة الاستخدام.

* دعم أصلي لبروتوكولات متعددة مثل **OpenVPN، Xray، V2Ray، WireGuard، و Cloudflare Warp**
* تثبيت **Passwall 1 و Passwall 2** (بشكل فردي أو متزامن) لاتصال إنترنت مستقر مع توجيه حركة مرور مجزأ ومستمر
* مشروع يتم صيانته بنشاط وتحديثه باستمرار

## ✨ الميزات

* **تثبيت رسومي بنقرة واحدة**: تثبيت سهل في LuCI بعد الإعداد الأولي
* **إعداد تلقائي بالكامل**: كل شيء يعمل بأمر واحد
* **دعم Passwall المزدوج**: تشغيل Passwall 1 و 2 في نفس الوقت على نفس جهاز التوجيه
* **Exroot سهل**: توسيع مساحة التخزين بنقرة واحدة (إذا كان USB متاحًا)
* **أدوات X86**: تحويل Linux x86/x64 إلى جهاز توجيه OpenWrt قوي
* **إعداد سريع لشبكة Wi-Fi**: تكوين شبكة Wi-Fi ببساطة عن طريق إدخال SSID وكلمة المرور
* **منظف الذاكرة**: تحرير ذاكرة الوصول العشوائي (RAM) بنقرة واحدة
* **حزم إضافية**: OpenVPN، Sing-box، SoftEther، والمزيد (لمساحة تخزين > 512 ميجابايت)
* **تثبيت XRAY الذكي**: يقوم بتثبيت XRAY على tmpfs إذا كانت مساحة التخزين محدودة
* **توجيه مُحسَّن**: توجيه مباشر لعناوين IP/نطاقات إيران لتحسين الأداء
* **تحسينات الأداء**: سمة جديدة، إصلاح WARP، مفتاح إيقاف افتراضي، XRAY Fragment TLS Hello

## 📡 البروتوكولات المدعومة

| البروتوكول | نواة XRAY | نواة SING-BOX |
| --- | --- | --- |
| **VLESS** | ✅ | ✅ |
| **VMESS** | ✅ | ✅ |
| **REALITY** | ✅ | ❌ |
| **TROJAN** | ✅ | ✅ |
| **HYSTERIA2** | ❌ | ✅ |
| **TUIC** | ❌ | ✅ |
| **Shadowsocks** | ✅ | ✅ |
| **WireGuard** | ✅ | ✅ |
| **SOCKS** | ✅ | ✅ |
| **HTTP** | ✅ | ✅ |

## 📶 أجهزة التوجيه الموصى بها

* x86/64
* Google WiFi (Gale)
* Linksys EA8300 / E8450 / EA7500 / EA8100
* Belkin rt3200
* GL-iNet GL-A1300 / AR300M (NOR)
* Xiaomi AX3000T / AX3600 / AX3200 / AX6000
* TP-Link C6 v3
* Mikrotik Hap ac2
* ASUS RT-N66U
* Netgear R7800
* ~~Xiaomi 4a Gigabit~~

## ⚡ التثبيت السريع

للتثبيت السريع، قم بتشغيل الأمر التالي في طرفية SSH لجهاز التوجيه الخاص بك:


```bash
sh -c "$(curl -sL https://peditxos.ir/install)"
``` 

بعد هذه الخطوة، يمكن إدارة كل شيء في المستقبل عبر **واجهة ويب LuCI**.

## 🏗️ منشئ البرامج الثابتة

قم ببناء صورة برنامج OpenWrt الثابت المخصصة الخاصة بك مع ملحقات PeDitXOS الرسمية باستخدام خدمتنا عبر الإنترنت:
👈 [ابدأ البناء](https://peditxos.ir)

## 🙏 شكر خاص

* [PeDitX](https://github.com/peditx)
* [PeDitXRT](https://github.com/peditx/peditxrt)
* [OpenWrt](https://github.com/openwrt)
* [ImmortalWrt](https://github.com/immortalwrt)
* [Bootstrap Theme](https://github.com/twbs/bootstrap)
* [Mohamadreza Broujerdi](https://t.me/MR13_B)
* [Sia7ash](https://github.com/Sia7ash)


© 2018–2025 PeDitX. كل الحقوق محفوظة.
للحصول على الدعم أو الاستفسارات، انضم إلينا على [Telegram](https://t.me/peditx).
