# build_react_app

Учебный проект для изучения ручной сборки React-приложения на JavaScript/TypeScript и понимания того, как устроен процесс сборки фронтенд-приложений без готовых шаблонов.

## О проекте

Этот репозиторий использовался как практика по настройке инструментов сборки и инфраструктуры фронтенд-приложения с нуля. Основной акцент сделан не на логике приложения, а на понимании того, как:

- настраивается `webpack` для разработки и production-сборки;
- подключаются `TypeScript`, `Babel` и транспиляция кода;
- обрабатываются `CSS Modules` и `SCSS`;
- подключаются статические ассеты, например изображения и шрифты;
- генерируется итоговый `HTML` через `HtmlWebpackPlugin`;
- работает линтинг через `ESLint`;
- формируется итоговая папка `dist`.

## Стек

- `React 18`
- `TypeScript`
- `Webpack 5`
- `webpack-dev-server`
- `Babel`
- `ESLint`
- `Prettier`
- `Sass / SCSS`
- `CSS Modules`

## Скрипты

```bash
npm start
```

Запуск dev-сервера на основе `webpack-dev-server`.

```bash
npm run build
```

Production-сборка проекта в папку `dist`.

## Структура проекта

```text
.
|-- public/
|   |-- index.html
|   `-- logo.png
|-- src/
|   |-- App.tsx
|   |-- app.module.css
|   `-- main.scss
|-- index.tsx
|-- declaration.d.ts
|-- webpack.common.ts
|-- webpack.dev.ts
|-- webpack.prod.ts
|-- tsconfig.json
|-- .babelrc
`-- .eslintrc.json
```

## Чему посвящен проект

Проект создавался как учебная площадка для изучения механизмов сборки JavaScript-приложений: от входной точки и резолва модулей до обработки стилей, ассетов и формирования production-артефактов.

