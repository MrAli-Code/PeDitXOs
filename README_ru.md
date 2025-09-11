# PeDitXOS Tools  

## Выбор языка:

[**English**](README.md) | [**فارسی**](README_fa.md) | [**中文**](README_zh.md) | [**Русский**](README_ru.md)

![PeDitX Banner](https://raw.githubusercontent.com/peditx/luci-theme-peditx/refs/heads/main/luasrc/brand.png)  

---

## 🚀 Что такое PeDitXOS?  
**PeDitXOS** — это набор скриптов, который превращает ваше устройство OpenWrt в мощный, современный и удобный шлюз.  

- Поддержка множества протоколов: **OpenVPN, Xray, V2Ray, WireGuard, Cloudflare Warp**  
- Установка **Passwall 1 и Passwall 2** (отдельно или одновременно) для стабильного соединения и маршрутизации  
- Активно поддерживаемый и постоянно обновляемый проект  

---

## ✨ Особенности  
- **Графическая установка в один клик** через LuCI  
- **Полностью автоматическая настройка** одной командой  
- **Одновременная работа Passwall 1 и 2**  
- **Easy Exroot**: расширение памяти с помощью USB  
- **Инструменты для X86**: превращение Linux x86/x64 в маршрутизатор OpenWrt  
- **Быстрая настройка Wi-Fi** (только SSID + пароль)  
- **Очистка памяти RAM** в один клик  
- **Дополнительные пакеты**: OpenVPN, Sing-box, SoftEther и др.  
- **Умная установка XRAY** на tmpfs при ограниченном хранилище  
- **Оптимизированная маршрутизация** для IP/доменов Ирана  
- **Улучшения производительности**: новая тема, исправленный WARP, Kill Switch по умолчанию, XRAY Fragment TLS Hello  

---

## 📡 Поддерживаемые протоколы  

| Протокол      | XRAY Core | SING-BOX Core |
|---------------|-----------|---------------|
| **VLESS**     | ✅         | ✅             |
| **VMESS**     | ✅         | ✅             |
| **REALITY**   | ✅         | ❌             |
| **TROJAN**    | ✅         | ✅             |
| **HYSTERIA2** | ❌         | ✅             |
| **TUIC**      | ❌         | ✅             |
| **Shadowsocks** | ✅       | ✅             |
| **WireGuard** | ✅         | ✅             |
| **SOCKS**     | ✅         | ✅             |
| **HTTP**      | ✅         | ✅             |

---

## 📶 Рекомендуемые роутеры  
- Google WiFi (Gale)  
- Linksys EA8300 / E8450 / EA7500 / EA8100  
- Belkin rt3200  
- GL-iNet GL-A1300 / AR300M (NOR)  
- Xiaomi AX3000T / AX3600 / AX3200 / AX6000  
- TP-Link C6 v3  
- Mikrotik Hap ac2  
- ASUS RT-N66U  
- Netgear R7800  
- ~~Xiaomi 4a Gigabit~~  

---

## ⚡ Быстрая установка  
Для быстрой установки выполните в SSH терминале роутера:  

```bash
sh -c "$(curl -sL https://peditxos.ir/install)"
```  

После этого вся настройка выполняется через **веб-интерфейс LuCI**.  

---

## 🏗️ Сборка прошивки  
Соберите собственный образ OpenWrt с официальными плагинами PeDitXOS:  
👉 [Начать сборку](https://peditxos.ir)  

---

## 🙏 Благодарности  

- [PeDitX](https://github.com/peditx)  
- [PeDitXRT](https://github.com/peditx/peditxrt)  
- [OpenWrt](https://github.com/openwrt)  
- [ImmortalWrt](https://github.com/immortalwrt)  
- [Bootstrap Theme](https://github.com/twbs/bootstrap)  


---

© 2018–2025 PeDitX. Все права защищены.  
Поддержка и вопросы: [Telegram](https://t.me/peditx).  
