# CSS-калькулятор

Одностраничный интерактивный справочник по CSS: 32 панели с ползунками, превью и готовым кодом, который можно скопировать. Дизайн — CSS Studio.

![CSS-калькулятор](screenshot.jpg)

## Что внутри

**Значения**
- Углы в CSS — deg / turn / rad / grad
- RGB, HEX, HSL — конвертеры цвета с альфой

**Движение**
- `translate`, `transform`, `transition`, кривая `cubic-bezier`
- `@keyframes` (многошаговый), анимация цвета через `@property`
- 3D-трансформации: `perspective` (px/em/rem), `perspective-origin` мышкой, `translate3d`, `rotate3d`, `scale3d`, `transform-style`, `backface-visibility`

**Оформление**
- `box-shadow`, многослойная тень, `text-shadow`
- Стекломорфизм (`backdrop-filter`)
- `filter` (9 функций + `drop-shadow` + SVG-фильтры через `url()`)
- `backdrop-filter` (стекло)
- `clip-path` и `text-stroke`
- `mix-blend-mode` (3 слоя) и `background-blend-mode` (свой фон-файл)
- Паттерны, градиентный текст, типографика, border/outline

**Градиенты**
- `linear-gradient`, `radial-gradient`, `conic-gradient` — редактор стопов, `repeating`, до 5+ цветов

## Как пользоваться

1. Открыть `index.html` в браузере (или включить GitHub Pages).
2. Выбрать панель во вкладках.
3. Крутить ползунки и смотреть превью.
4. Скопировать готовый CSS из блока внизу.

Кнопка **«очистить значение»** возвращает текущую панель к исходным значениям.

## Технически

- один HTML-файл, без сборки и зависимостей;
- ванильный CSS и JS;
- тёмная тема, адаптив, сайдбар с поиском;
- глубокие ссылки: `#linear-gradient`, `#transform-3d`, `#text-stroke`;

## Лицензия

MIT — используйте как хотите.
