# CDN и облачные технологии

Статический сайт на Jekyll с фокусом на CDN и облачные технологии. Демонстрирует современные подходы к разработке статических сайтов с использованием Tailwind CSS и автоматизированной сборки.

## 🛠 Технологический стек

- **Jekyll** — генератор статических сайтов
- **Tailwind CSS** — утилитарный CSS-фреймворк
- **PostCSS** — обработка CSS
- **GitHub Actions** — CI/CD автоматизация
- **HTML-validate** — валидация HTML
- **html-minifier-terser** — минификация HTML

## 📁 Структура проекта

```
├── _config.yml              # Конфигурация Jekyll
├── _layouts/                # Шаблоны страниц
├── _includes/               # Частичные шаблоны
├── assets/                  # Статические ресурсы
│   ├── css/
│   └── js/
├── Gemfile                  # Ruby зависимости
├── package.json             # Node.js зависимости
├── tailwind.config.js       # Конфигурация Tailwind
├── postcss.config.js        # Конфигурация PostCSS
├── index.html               # Главная страница
└── about.md                 # Страница "О нас"
```

## 🚀 Установка и запуск

### 1. Клонирование репозитория

```bash
git clone https://github.com/your-username/cdn-site.git
cd cdn-site
```

### 2. Установка зависимостей

```bash
# Ruby зависимости
bundle install

# Node.js зависимости
npm install
```

### 3. Сборка CSS

```bash
npm run css:build
```

### 4. Запуск локального сервера

```bash
npm run serve
```

Сайт будет доступен по адресу: http://127.0.0.1:4000

## 📝 Доступные команды

```bash
# Сборка сайта
npm run build

# Запуск локального сервера
npm run serve

# Сборка CSS
npm run css:build

# Сборка CSS в режиме наблюдения
npm run css:watch

# Тестирование
npm run test
```

## 🎨 Кастомизация

### Изменение цветовой схемы

Отредактируйте `tailwind.config.js`:

```javascript
theme: {
  extend: {
    colors: {
      primary: '#3B82F6',
      secondary: '#1E40AF',
      accent: '#60A5FA'
    }
  }
}
```

### Добавление новых страниц

1. Создайте файл `.md` или `.html` в корне проекта
2. Добавьте front-matter:

```yaml
---
layout: page
title: "Название страницы"
---
```

## 📊 О проекте

Сайт содержит информацию о:

- Статистике использования CDN (2022 год)
- Отечественных CDN провайдерах
- Современных подходах к развертыванию статических сайтов

## 📄 Лицензия

MIT License
