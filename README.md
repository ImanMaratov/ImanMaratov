<!-- README.md для Iman Maratov (Frontend Developer) -->
<!-- Скопируй весь этот файл в README.md -->

<!--
  Примечание:
  - GitHub рендерит SVG-изображения, поэтому здесь много inline-SVG в виде data-URI.
  - Если что-то в превью не видно (редко) — сообщи, и дам альтернативы (GIF / хостинг изображений).
-->

<p align="center">
  <!-- Gradient banner (animated SVG) -->
  <img alt="Iman Maratov - banner" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="1000" height="220" viewBox="0 0 1000 220">
    <defs>
      <linearGradient id="g" x1="0" x2="1">
        <stop offset="0" stop-color="%233a7bd5"/>
        <stop offset="0.5" stop-color="%2382c2ff"/>
        <stop offset="1" stop-color="%238a58ff"/>
      </linearGradient>
      <filter id="f" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="8" result="b"/>
        <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
    </defs>

    <rect width="100%" height="100%" rx="18" fill="url(%23g)"/>
    <g transform="translate(40,24)">
      <text x="0" y="48" font-family="Segoe UI, Roboto, Arial" font-size="40" fill="white" font-weight="700">Iman Maratov</text>
      <text x="0" y="88" font-family="Segoe UI, Roboto, Arial" font-size="20" fill="rgba(255,255,255,0.9)">Frontend Developer • React • TypeScript • Tailwind</text>

      <!-- animated tagline (moving circle + text fade) -->
      <g transform="translate(0,110)">
        <circle cx="8" cy="8" r="8" fill="white" opacity="0.14">
          <animate attributeName="cx" from="8" to="300" dur="4s" repeatCount="indefinite"/>
        </circle>
        <text x="26" y="12" font-family="Segoe UI, Roboto, Arial" font-size="14" fill="white" opacity="0.95">
          Crafting smooth UI & performant web apps
        </text>
      </g>
    </g>

    <!-- bouncing decor -->
    <g transform="translate(700,40)">
      <rect x="0" y="0" width="220" height="140" rx="12" fill="rgba(255,255,255,0.06)"/>
      <circle cx="30" cy="30" r="12" fill="white">
        <animate attributeName="cy" values="30;110;30" dur="2.2s" repeatCount="indefinite"/>
        <animate attributeName="cx" values="30;190;30" dur="3.1s" repeatCount="indefinite"/>
      </circle>
    </g>
  </svg>' width="100%" style="max-width:1000px; border-radius:12px; box-shadow: 0 8px 30px rgba(0,0,0,0.25);" />
</p>

---

# 👋 Привет — я **Iman Maratov**
**Junior Frontend Developer** — строю отзывчивые и приятные интерфейсы, фокус на React, TypeScript и Tailwind.  
Я открыт к новым проектам и коллаборациям.

---

## 🚀 Проекты
- [ImanShopp — интернет-магазин (React, Vite)](https://imanshopp.vercel.app/)  
- [Портфолио (React, Vite)](https://portfolioimanmaratov.vercel.app/)  
- [Hackaton Figmaproject (демо)](https://hacatonfigmaproject.vercel.app/)

---

## 📫 Контакты
Телефон: **+996 500 979 101**  
Telegram: **[@solweit](https://t.me/solweit)**  
Instagram: **[@maratovw_88](https://instagram.com/maratovw_88)**  
Email: **imanmaratov009@gmail.com**  

(Контактные данные взяты из твоего резюме/CV). :contentReference[oaicite:1]{index=1}

---

## 🧰 Технологии
Ниже — набор иконок языков/фреймфорков. Это inline-SVG — будут отображаться прямо в README.

<p align="center">
  <!-- JS -->
  <img alt="JavaScript" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 128 128">
    <rect width="128" height="128" rx="20" fill="%23F7DF1E"/>
    <text x="64" y="82" font-size="70" text-anchor="middle" font-family="Arial" fill="%23000">JS</text>
  </svg>' title="JavaScript" style="margin:4px;" />
  <!-- React -->
  <img alt="React" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="-12 -12 96 96">
    <circle cx="32" cy="32" r="10" fill="%23222"/>
    <g stroke="%2300D8FF" stroke-width="3" fill="none">
      <ellipse rx="32" ry="12" cx="32" cy="32" transform="rotate(0 32 32)"/>
      <ellipse rx="32" ry="12" cx="32" cy="32" transform="rotate(60 32 32)"/>
      <ellipse rx="32" ry="12" cx="32" cy="32" transform="rotate(120 32 32)"/>
    </g>
  </svg>' title="React" style="margin:4px;" />
  <!-- TS -->
  <img alt="TypeScript" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 128 128">
    <rect width="128" height="128" rx="18" fill="%23007ACC"/>
    <text x="64" y="86" font-size="60" text-anchor="middle" font-family="Arial" fill="white">TS</text>
  </svg>' title="TypeScript" style="margin:4px;" />
  <!-- HTML5 -->
  <img alt="HTML5" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 128 128">
    <path fill="%23E44D26" d="M19.5 4l9.6 107.6L64 124l34.9-12.4L108.5 4z"/>
    <text x="64" y="90" font-size="32" text-anchor="middle" font-family="Arial" fill="white">5</text>
  </svg>' title="HTML5" style="margin:4px;" />
  <!-- CSS3 -->
  <img alt="CSS3" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 128 128">
    <path fill="%231572B6" d="M19.5 4l9.6 107.6L64 124l34.9-12.4L108.5 4z"/>
    <text x="64" y="90" font-size="28" text-anchor="middle" font-family="Arial" fill="white">CSS</text>
  </svg>' title="CSS3" style="margin:4px;" />
  <!-- Tailwind (symbolic) -->
  <img alt="Tailwind CSS" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24">
    <path d="M2 12c4-6 9-6 14 0 0 0-4-6-14 0z" fill="%230062D3"/>
    <path d="M2 16c4-6 9-6 14 0 0 0-4-6-14 0z" fill="%2300A8FF" opacity="0.9"/>
  </svg>' title="Tailwind CSS" style="margin:4px;" />
  <!-- Figma (symbolic) -->
  <img alt="Figma" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 48 48">
    <rect width="48" height="48" rx="8" fill="%23FFF"/>
    <circle cx="16" cy="12" r="6" fill="%23FF7262"/>
    <rect x="16" y="6" width="12" height="12" rx="6" fill="%23F24E1E"/>
    <rect x="16" y="18" width="12" height="12" rx="6" fill="%23A259FF"/>
    <rect x="6" y="30" width="12" height="12" rx="6" fill="%2300AAB1"/>
  </svg>' title="Figma" style="margin:4px;" />
  <!-- Python / Java (symbolic) -->
  <img alt="Python" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 128 128">
    <rect rx="18" width="128" height="128" fill="%233776AB"/>
    <text x="64" y="82" font-size="40" text-anchor="middle" font-family="Arial" fill="white">Py</text>
  </svg>' title="Python" style="margin:4px;" />
  <img alt="Java" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 128 128">
    <rect rx="18" width="128" height="128" fill="%23C0171A"/>
    <text x="64" y="82" font-size="36" text-anchor="middle" font-family="Arial" fill="white">Jv</text>
  </svg>' title="Java" style="margin:4px;" />
</p>

---

## 🔥 Мини-игра / анимация (встроенный SVG)
Это небольшая визуальная «игрушка» — просто для эффекта на твоём README. Работает как анимация SVG:

<p align="center">
  <img alt="Mini game - bouncing ball" src='data:image/svg+xml;utf8,
  <svg xmlns="http://www.w3.org/2000/svg" width="640" height="140" viewBox="0 0 640 140">
    <rect width="640" height="140" rx="12" fill="rgba(10,10,10,0.04)"/>
    <rect x="24" y="24" width="592" height="92" rx="8" fill="url(%23g2)"/>
    <defs>
      <linearGradient id="g2" x1="0" x2="1"><stop offset="0" stop-color="%23ff9a9e"/><stop offset="1" stop-color="%23fecfef"/></linearGradient>
    </defs>

    <!-- paddles -->
    <rect x="60" y="60" width="6" height="20" rx="3" fill="%23000"/>
    <rect x="574" y="60" width="6" height="20" rx="3" fill="%23000"/>

    <!-- ball -->
    <circle cx="320" cy="70" r="10" fill="%23000000">
      <animate attributeName="cx" values="120;520;120" dur="2.6s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="40;100;40" dur="1.3s" repeatCount="indefinite"/>
    </circle>

    <!-- score (decorative) -->
    <text x="160" y="28" font-family="Arial" font-size="14" fill="%23000">IMAN</text>
    <text x="480" y="28" font-family="Arial" font-size="14" fill="%23000">YOU</text>
  </svg>' style="max-width:640px; border-radius:8px;" />
</p>

---

## ✨ Как использовать
1. Копируй весь этот файл в `README.md` в корне репо.  
2. Если хочешь — замени ссылки соцсетей на приватные профили/почту по желанию.  
3. Чтобы добавить кастомный GIF или большой баннер — загрузи в репозиторий и поменяй `src` у `<img>` на относительный путь.

---

## 🛠️ Рекомендации по улучшению (optionally)
- Для полной интерактивности (игра с клавиатурой) — лучше добавить `index.html` в репо и ссылаться на него в README (или использовать GitHub Pages).
- Можно заменить data-URI SVG на хостированные SVG или GIF, если хочешь более надёжный кросс-платформенный рендер.

---

Если хочешь, я:
- подготовлю отдельный `index.html` с тем же дизайном (адаптивный, с CSS-анимациями и реальной мини-игрой на JS),
- или дам версию README без inline-SVG (чтобы уменьшить размер файла),
- или оформлю README на английском.

Напиши, что предпочитаешь — и я прикреплю готовый `index.html` или внесу правки прямо в MD.
