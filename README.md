<div align="center">

# 🎨 mUI Live

**Живые обои в стиле Material You для Android.**

[![Android](https://img.shields.io/badge/Android-13%2B-green?style=flat-square&logo=android&logoColor=white)](#)
[![Java](https://img.shields.io/badge/Language-Java-orange?style=flat-square&logo=java)](#)
[![Material 3](https://img.shields.io/badge/Design-Material%203-purple?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](#)

<p align="center">
  <!-- ЗАМЕНИ ЭТИ ССЫЛКИ НА СВОИ СКРИНШОТЫ (загрузи их в папку screenshots) -->
  <img src="./screenshots/screen1.png" width="200" hspace="10"/>
  <img src="./screenshots/screen2.png" width="200" hspace="10"/>
  <img src="./screenshots/screen3.png" width="200" hspace="10"/>
</p>

</div>

---

## ✨ Особенности

- 🎨 **Динамические цвета Material You:** Полная интеграция с системной палитрой вашего устройства.
- 🌈 **Кастомная монохромная палитра:** Выбирайте базовый цвет, и приложение сгенерирует идеальные оттенки для фона и фигур.
- 🔄 **Бесконечная анимированная сетка:** Плавная прокрутка (параллакс) при перелистывании рабочего стола.
- ⚙️ **Гибкая настройка:** Управляйте размером фигур (авто-сжатие сетки), скоростью вращения и формой краев.
- ⚡ **Экономия батареи:** Отрисовка останавливается, когда обои не видны.

## 🚀 Установка

1. Скачайте последний релизный `.apk` файл из раздела [Releases](https://github.com/rixa8/mUI-Live/releases).
2. Установите приложение на устройство (Android 13+).
3. Откройте приложение, настройте внешний вид и нажмите **«Установить обои»**.

## 🛠️ Сборка из исходников

Если вы хотите собрать проект самостоятельно:

```bash
# Клонируйте репозиторий
git clone https://github.com/rixa8/mUI-Live.git

# Откройте проект в Android Studio (требуется Android Studio Hedgehog или новее)
# Нажмите Build -> Make Project (или Ctrl+F9)
💡 Как это работает
Приложение использует WallpaperService для отрисовки фигур (кругов, шестиугольников, "цветков" и squircle) на Canvas.
Сетка генерируется математически и смещается при свайпах для эффекта бесконечности. Цвета генерируются в цветовом пространстве HSV из одного базового оттенка для создания гармоничной монохромной палитры.

👨‍💻 Автор
Rixa

TikTok: @s_l_i_m_t_e_c_h

GitHub: @rixa8

📄 Лицензия
Этот проект распространяется под лицензией MIT. Подробности смотрите в файле LICENSE.
