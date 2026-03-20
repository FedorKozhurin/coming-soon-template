# coming-soon-template
Interactive waitlist page. Vanilla JS, CSS glassmorphism, and 3D hover effects.

Минималистичный лендинг-заглушка (Coming Soon) для будущего сайта молодежной организации. 

Проект реализован в виде одного `index.html` файла без использования сторонних фреймворков и библиотек. Основной фокус сделан на плавные анимации, свет и оптимизацию под мобильные устройства.

[![Deploy Status](https://img.shields.io/badge/deploy-GitHub_Pages-success?style=flat-square)](#)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E)

## ⚡ Особенности реализации

- **Zero Dependencies:** Чистый HTML, CSS и Vanilla JS без npm-пакетов.
- **Glassmorphism UI:** Использование `backdrop-filter` и многослойных градиентов для создания объема.
- **3D-эффекты:** Интерактивные `rotateX/Y` трансформации, привязанные к движению мыши (оптимизировано через `requestAnimationFrame`).
- **Адаптивность:** Полная поддержка мобильных устройств с использованием `clamp()`, `100dvh` и переменных `safe-area-inset`.
- **A11y & UX:** Учет `prefers-reduced-motion` для отключения анимаций, скрытые honeypot-поля для защиты от спама.
