Это базовый скелет будущего сайта, разработанный совместно с моделью gemma4:31b-cloud. Промпт написан на базе предидущей работы и персонализирован исходя из отпечатка общения Атора и этой языковой модели. Сам сайт собран на базе Open Cod с помощью языковой модели GLM-5.3.
Prompt in Eng Leng [Task: Create a high-fidelity, professional prototype for a Men's Information Hub named "NEONPULSE". The site is a high-tech aggregator for AI, Politics, Auto, Tech, Style, and Gaming.

1. Visual Identity (Cyber-Minimalism):

Color Palette:
Background: Deep Black #0a0a0a.
Primary Accent: Neon Green #39FF14.
Text: Pure White for headings, Muted Gray #A0A0A0 for body text.
Aesthetic:
High-contrast "Dark Mode".
Use Glassmorphism for cards (very dark gray background #151515 with subtle borders).
Neon glow effects (box-shadow) for buttons and active elements.
Typography: Bold, oversized sans-serif for main headings; mono-spaced fonts for tags, dates, and IDs to create a "database/terminal" feel.
2. Page Structure & Layout:

Header: Sticky minimalist nav. Logo "NEONPULSE" on the left, categories on the right (ИИ, Политика, Авто, Технологии, Стиль, Гейминг).
Hero Section:
A "Trending Now" badge with a neon glow.
An oversized, bold main headline where one or two key words are highlighted in Neon Green.
A short, impactful summary and two buttons: "Читать статью" (Primary Neon) and "Смотреть брифинг" (Outline style).
Content Grid (Latest Dispatches):
A responsive grid of news cards.
Each card must contain:
A category tag in a small mono-font box with a neon accent.
The date (e.g., "Oct 24, 2026").
A bold title and a brief excerpt.
A "Читать далее $\rightarrow$" link.
A unique article ID in the bottom right corner (e.g., #081, #082) to simulate an archive.
Sidebar:
"Фильтр по категориям" list with article counts (e.g., "Все — 12", "ИИ — 2").
A "Newsletter" subscription box with a neon "Join" button.
A "Status" indicator: "Все системы работают" with a small pulsing green dot.
Footer: Minimalist design. Branding text: "Powered by AI and The Engineer Vadim Tairov".
3. Technical Requirements:

Language: All interface text and content must be in Russian.
Stack: Single-file solution using HTML5, Tailwind CSS, and Vanilla JavaScript.
Data Handling: Use a JSON-like array in JavaScript to populate the news cards. This allows for easy content updates.
Responsiveness: Fully adaptive for Mobile, Tablet, and Desktop.
Animations: Smooth fade-in for blocks on load, and subtle lift/glow effects for cards on hover.
Deliverable: Provide the complete, production-ready code in a single file. Focus on a "wow-effect" visual that looks like a premium tech media portal, not a generic template.]

Текст промпат на русском[Задача: Создать высокоточный, профессиональный прототип информационного хаба для мужчин под названием «NEONPULSE». Сайт представляет собой высокотехнологичный агрегатор новостей по темам: ИИ, Политика, Авто, Технологии, Стиль и Гейминг.

1. Визуальная идентичность (Кибер-минимализм):

Цветовая палитра:
Фон: Глубокий черный #0a0a0a.
Основной акцент: Неоновый зеленый #39FF14.
Текст: Чистый белый для заголовков, приглушенный серый #A0A0A0 для основного текста.
Эстетика:
Высококонтрастный «Темный режим».
Использование «стеклянного» эффекта (Glassmorphism) для карточек (очень темно-серый фон #151515 с тонкими границами).
Эффекты неонового свечения (box-shadow) для кнопок и активных элементов.
Типографика: Жирные, массивные шрифты без засечек для главных заголовков; моноширинные шрифты для тегов, дат и ID, чтобы создать ощущение «базы данных» или «терминала».
2. Структура страницы и макет:

Шапка (Header): Минималистичное липкое (sticky) меню. Логотип «NEONPULSE» слева, категории справа (ИИ, Политика, Авто, Технологии, Стиль, Гейминг).
Главный блок (Hero Section):
Бейдж «В тренде» с неоновым свечением.
Огромный, жирный главный заголовок, где одно или два ключевых слова выделены неоновым зеленым.
Короткое, емкое описание и две кнопки: «Читать статью» (Основная, неоновая) и «Смотреть брифинг» (Контурный стиль).
Сетка контента (Последние сводки):
Адаптивная сетка новостных карточек.
Каждая карточка должна содержать:
Тег категории в маленьком прямоугольнике с моно-шрифтом и неоновым акцентом.
Дату (например, «24 окт 2026»).
Жирный заголовок и краткий отрывок текста.
Ссылку «Читать далее $\rightarrow$».
Уникальный ID статьи в нижнем правом углу (например, #081, #082) для имитации архива.
Боковая панель (Sidebar):
Список «Фильтр по категориям» с количеством статей (например, «Все — 12», «ИИ — 2»).
Блок подписки на рассылку с неоновой кнопкой «Присоединиться».
Индикатор статуса: «Все системы работают» с маленькой пульсирующей зеленой точкой.
Подвал (Footer): Минималистичный дизайн. Текст бренда: «Powered by AI and The Engineer Vadim Tairov».
3. Технические требования:

Язык: Весь интерфейс и контент должны быть на русском языке.
Стек: Решение в одном файле, использующее HTML5, Tailwind CSS и чистый JavaScript (Vanilla JS).
Работа с данными: Использовать массив в формате JSON в JavaScript для наполнения карточек новостями. Это позволит легко обновлять контент.
Адаптивность: Полная поддержка мобильных устройств, планшетов и ПК.
Анимации: Плавное появление блоков при загрузке страницы и легкий эффект приподнимания/свечения карточек при наведении.
Результат: Предоставить полный, готовый к работе код в одном файле. Фокус на визуальном «wow-эффекте», чтобы сайт выглядел как премиальный тех-портал, а не как шаблонный сайт.]
# intensive # Zerocoder # VadimTairov # TheEngineer
