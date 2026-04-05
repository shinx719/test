<div align="center">
</div>

---

## 📁 Структура папок

### ✅ Категории

| Папка | Функции | Кол-во примеров |
|-------|---------|-----------------|
| **🎯 align** | align-content, align-items, align-self | 3 |
| **⏱️ animation** | animation-delay, duration, direction, fill-mode, iteration-count, name, play-state, timing-function | 8 |
| **🎨 background** | background-color, image, position, repeat, size, attachment, clip, origin | 9 |
| **📏 border** | border-width, style, color, radius, и варианты для каждой стороны | 27 |
| **📦 box** | box-shadow, box-sizing | 2 |
| **📋 column** | column-count, column-gap, column-width | ~ |
| **↔️ flex** | flex-basis, flex-direction, flex-flow, flex-grow, flex-shrink, flex-wrap | ~ |
| **🔤 font** | font-family, font-size, font-style, font-variant, font-weight | ~ |
| **⚡ grid** | grid-area, grid-column, grid-row, grid-template, и другие | ~ |
| **📌 list** | list-style-type, list-style-position, list-style-image | ~ |
| **➡️ margin** | margin-top, margin-bottom, margin-left, margin-right | ~ |
| **📐 max** | max-width, max-height | ~ |
| **📏 min** | min-width, min-height | ~ |
| **🔲 outline** | outline-width, outline-style, outline-color | ~ |
| **💧 overflow** | overflow, overflow-x, overflow-y, overflow-wrap | ~ |
| **🔹 padding** | padding-top, padding-bottom, padding-left, padding-right | ~ |
| **🎪 random** | display, position, color, cursor, z-index, opacity и другие | ~ |
| **📝 text** | text-align, text-decoration, text-indent, text-shadow, text-transform | ~ |
| **🔄 transform** | transform, transform-origin (rotate, scale, translate, skew) | ~ |
| **✨ transition** | transition-duration, transition-delay, transition-property, transition-timing-function | ~ |
| **💬 word** | word-break, word-spacing | ~ |

---

## 🎨 Файловая структура

```
test/
├── 📄 README.md              # Этот файл
├── 📄 test.html              # 🏠 Главная страница
├── 📄 sidebar.html           # 📑 Боковая панель навигации
├── 🎨 style.css              # 🌈 Глобальные стили
├── 🎨 sidebar.css            # 📋 Стили боковой панели
├── 🖼️ 1111.jpg               # Изображение для примеров
├── 🖼️ im111age.png           # Изображение для примеров
├── 🖼️ jt.png                 # Иконка для примеров
├── 📜 copy_container.js      # JS для копирования кода
│
├── 📁 align/                 # Выравнивание
│   ├── align.css
│   ├── align-content.html
│   ├── align-items.html
│   └── align-self.html
│
├── 📁 animation/             # Анимации
│   ├── animation.html
│   ├── animation-delay.html
│   ├── animation-direction.html
│   ├── animation-duration.html
│   ├── animation-fill-mode.html
│   ├── animation-iteration-count.html
│   ├── animation-name.html
│   ├── animation-play-state.html
│   └── animation-timing-function.html
│
├── 📁 background/            # Фоны
│   ├── background.html
│   ├── background-attachment.html
│   ├── background-clip.html
│   ├── background-color.html
│   ├── background-image.html
│   ├── background-origin.html
│   ├── background-position.html
│   ├── background-repeat.html
│   └── background-size.html
│
├── 📁 border/                # Границы (27 файлов)
│   ├── border.html
│   ├── border-bottom.html
│   ├── border-bottom-color.html
│   ├── border-bottom-left-radius.html
│   ├── border-bottom-right-radius.html
│   ├── border-bottom-style.html
│   ├── border-bottom-width.html
│   ├── border-collapse.html
│   ├── border-color.html
│   ├── border-left.html
│   ├── border-left-color.html
│   ├── border-left-style.html
│   ├── border-left-width.html
│   ├── border-radius.html
│   ├── border-right.html
│   ├── border-right-color.html
│   ├── border-right-style.html
│   ├── border-right-width.html
│   ├── border-style.html
│   ├── border-top.html
│   ├── border-top-color.html
│   ├── border-top-left-radius.html
│   ├── border-top-right-radius.html
│   ├── border-top-style.html
│   ├── border-top-width.html
│   └── border-width.html
│
├── 📁 box/                   # Box model
│   ├── box-shadow.html
│   └── box-sizing.html
│
├── 📁 column/                # Колонки
├── 📁 flex/                  # Flexbox
├── 📁 font/                  # Шрифты
├── 📁 grid/                  # CSS Grid
├── 📁 list/                  # Списки
├── 📁 margin/                # Отступы
├── 📁 max/                   # Максимум
├── 📁 min/                   # Минимум
├── 📁 outline/               # Контуры
├── 📁 overflow/              # Переполнение
├── 📁 padding/               # Padding
├── 📁 random/                # Другие
├── 📁 text/                  # Текст
├── 📁 transform/             # Трансформации
├── 📁 transition/            # Переходы
└── 📁 word/                  # Слова
```

---

## 💡 Примеры использования

### 1️⃣ Flexbox
```css
.container {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 10px;
}

.item {
  flex: 1;
  flex-grow: 1;
}
```

### 2️⃣ CSS Grid
```css
.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 20px;
  grid-auto-flow: row;
}
```

### 3️⃣ Анимации
```css
@keyframes slideIn {
  from {
    transform: translateX(-100%);
    opacity: 0;
  }
  to {
    transform: translateX(0);
    opacity: 1;
  }
}

.animated {
  animation: slideIn 0.5s ease-in-out forwards;
}
```

### 4️⃣ Фоны и градиенты
```css
.background {
  background: linear-gradient(45deg, #ff0000, #0000ff);
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}
```

### 5️⃣ Borders и shadows
```css
.card {
  border: 2px solid #ccc;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
```

---

- 🌐 GitHub: [@shinx719](https://github.com/shinx719)
- 💼 Проект создан в 2026 году

**Made with ❤️ by shinx719**
**Last Updated:** April 5, 2026 | **Version:** 1.0.0

</div>
