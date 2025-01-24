# Фитнес-помощник

Фитнес-помощник — это веб-приложение, которое помогает пользователям рассчитать суточную норму калорий и распределение БЖУ (белки, жиры, углеводы). Проект включает две версии сайта: обычную и версию для слабовидящих.

---

## Оглавление
1. [Функциональность](#функциональность)
2. [Структура проекта](#структура-проекта)
3. [Критерии выполнения](#критерии-выполнения)
4. [Инструкция по использованию](#инструкция-по-использованию)
5. [Технические требования](#технические-требования)
6. [Скриншоты](#скриншоты)

---

## Функциональность

### Основные функции:
1. **Главная страница**:
   - Информация о фитнесе.
   - Преимущества фитнеса.
   - Советы для начинающих.
   - Популярные виды фитнеса.

2. **Калькулятор калорий**:
   - Форма для ввода данных (вес, рост, возраст, пол, уровень активности, цель).
   - Расчет суточной нормы калорий и БЖУ.

3. **Результаты расчета**:
   - Отображение результатов после отправки формы.

4. **Версия для слабовидящих**:
   - Увеличенный размер шрифта.
   - Высококонтрастный режим.
   - Адаптивная верстка.

---

## Структура проекта

### Файлы и папки:
- **index.html** — Главная страница (обычная версия).
- **calculator.html** — Страница калькулятора (обычная версия).
- **results.html** — Страница с результатами (обычная версия).
- **index-accessibility.html** — Главная страница (версия для слабовидящих).
- **calculator-accessibility.html** — Страница калькулятора (версия для слабовидящих).
- **results-accessibility.html** — Страница с результатами (версия для слабовидящих).
- **styles.css** — Основные стили (обычная версия).
- **styles-accessibility.css** — Стили для слабовидящих.

---

## Критерии выполнения

### Раздел 1. Анализ и проектирование (20 баллов)
1. **Многостраничный сайт** (минимум 2 страницы):
   - Главная страница.
   - Страница калькулятора.

2. **Код проходит валидацию** (HTML/CSS):
   - Использованы валидаторы:
     - [HTML Validator](https://validator.w3.org/)
     - [CSS Validator](https://jigsaw.w3.org/css-validator/).

3. **Адаптивная верстка** (минимум для трех размеров экранов):
   - Мобильные устройства (до 600px).
   - Планшеты (600px — 1024px).
   - Десктопы (1024px и выше).

4. **Доступность для лиц с ограниченными возможностями**:
   - Увеличенный размер шрифта.
   - Высококонтрастный режим.
   - Семантическая разметка и атрибуты ARIA.

5. **User-friendly дизайн**:
   - Плавные переходы.
   - Интуитивно понятная навигация.

6. **Репозиторий проекта**:
   - Регулярные коммиты.

### Раздел 2. Реализация (40 баллов)
1. **Единое оформление страниц**:
   - Общая шапка и подвал.
   - Кликабельное меню.

2. **Мультимедиа информация**:
   - Изображения на главной странице.

3. **Форма для заполнения пользователем**:
   - Форма калькулятора с обязательными полями.
   - Перенаправление на страницу с результатами.

4. **Логичная анимация**:
   - Плавное появление секций.

---

## Инструкция по использованию

### Как запустить проект:
1. Скачайте или клонируйте репозиторий.
2. Откройте файл `index.html` в браузере для обычной версии.
3. Откройте файл `index-accessibility.html` для версии для слабовидящих.

### Как использовать калькулятор:
1. Перейдите на страницу калькулятора.
2. Заполните форму:
   - Вес (кг).
   - Рост (см).
   - Возраст (лет).
   - Пол.
   - Уровень активности.
   - Цель (снижение веса, рекомпозиция, набор массы).
3. Нажмите кнопку "Рассчитать".
4. Результаты отобразятся на странице с результатами.

---

## Технические требования

### Используемые технологии:
- HTML5.
- CSS3.
- Адаптивная верстка (медиа-запросы).
- Семантическая разметка и ARIA.

### Браузеры:
- Проект протестирован в современных браузерах:
  - Google Chrome.
  - Mozilla Firefox.
  - Microsoft Edge.

---

## Скриншоты

### Главная страница (обычная версия):
![Главная страница](img\main.png)

### Калькулятор (версия для слабовидящих):
![Калькулятор](img\calculator-accessibility.png)

### Результаты расчета:
![Результаты](img\result.png)

---

## Автор
Олейников К.А.
