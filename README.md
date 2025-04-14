# webrazr

## 📌 Описание
webrazr — это проект, разработанный для  для проведения когнитивных тестов, которые помогают определить уровень внимания, памяти, логического мышления и скорости обработки информации. 
Этот инструмент может использоваться для самооценки, научных исследований или психологических тестирований.
Проект включает различные тесты и другие модули, разработанные командой.

## 📂 Структура проекта
- **node_modules/** – Директория зависимостей npm.
  - `bin/`-Папка, содержащая исполнимые файлы для пакетов, установленных через npm. Она может содержать CLI-интерфейсы или утилиты, которые можно использовать из командной строки.
  - `vue-global-types/` - Пакет,связанный с типами для **Vue.js**. Он содержит типы для TypeScript, которые помогают интегрировать Vue.js в проект с использованием TypeScript.
  - `babel/`-  Папка с зависимостями, связанными с **Babel**. Это инструмент для транспиляции кода JavaScript, который позволяет использовать современные возможности языка, а затем преобразовать код в более совместимую версию для различных браузеров.
  - `vue/`- Это основная библиотека **Vue.js**, популярного фреймворка для создания интерфейсов. Содержит код, необходимый для работы самого фреймворка, если проект использует Vue.
  - `csstype/`- Пакет с типами для работы с CSS в **TypeScript**. Это помогает при разработке с использованием TypeScript для типизации CSS свойств.
  - `entities/`-  Пакет для работы с HTML-сущностями. Он полезен для безопасной обработки данных и отображения специальных символов.
  - `entree-walker/`- Пакет для обхода структуры данных,связанный с обходом деревьев DOM или JSON.
  - `magic-string/`- Библиотека для манипуляции строками в JavaScript. Она позволяет эффективно изменять строки без изменения их исходного содержания.
  - `nanoid/`- Легковесная библиотека для генерации уникальных идентификаторов (ID).
  - `picocolors/`- Минималистичная библиотека для работы с цветами в терминале.
  - `postcss/`-  инструмент для обработки CSS. Он позволяет использовать плагины для различных задач, таких как добавление автопрефиксов, минификация стилей и другие оптимизации CSS.
  - `source-map-js/`- Библиотека для работы с **source maps** в JavaScript. Source maps связывают скомпилированный код с исходным кодом, что упрощает отладку и анализ ошибок в транспилированном коде.
  - `vue-router/`— официальная библиотека для маршрутизации в **Vue.js**. Она используется для управления навигацией и переходами между страницами или компонентами в одностраничных приложениях (SPA).

- **.vscode/**– Настройки редактора Visual Studio Code.
  - `launch.json`— используется для настройки конфигурации отладки. В нем определена настройка для запуска и отладки проекта в браузере Chrome.
 
  - 
- **django-back/** – Основная директория backend проекта.
    - `backend/` и `api/`  – 2 приложения, содержащие серверную логику и API для обработки запросов, связанных с тестами.
    - `package-lock.json`– Файл, описывающий зафиксированные версии установленных зависимостей.
    - `package.json` – Основной файл конфигурации проекта, содержащий информацию о зависимостях, скриптах и других настройках.
    - `static` - Файл, содержащий билд фронта для продакшн версии.Статические файлы (например, изображения, стили, скрипты), используемые для отображения интерфейса тестов.
    -  `manage.py` – Скрипт для управления проектом, например, для миграций, запуска сервера и других задач.
    - `urls.py` – Файл, в котором описаны маршруты (URLs) для обработки запросов в проекте.
- **my-vue-app/** – Основная директория frontend проекта.  
    - `scr/components/` – Папка с компонентами проекта.
    - `node_modules/` – Директория зависимостей npm для данного проекта.
    - `dist/` – билд фронтенд части проекта.
    - `Tests/` – Основные тесты для оценки когнитивных функций.
    - `Auth/` – Авторизация и регистрация пользователей.

## 🛠 Используемые библиотеки
- **Express** – Фреймворк для создания сервера и обработки API-запросов.
- **SQLite** – Легковесная реляционная база данных, используется для хранения результатов тестов (файл **`db.sqlite3`**).
- **Axios** – Библиотека для выполнения HTTP-запросов к серверу.
- **Jest** – Инструмент для тестирования кода.
- **Vue.js** – Фреймворк для создания пользовательских интерфейсов.
- **Vue Router** – Библиотека для маршрутизации в **Vue.js**.
- **PostCSS** – Инструмент для обработки CSS с использованием плагинов для автопрефиксов, минификации и других задач.
- **Babel** – Транспилятор JavaScript для использования современных возможностей языка с последующей компиляцией в совместимую версию.
- **Nanoid** – Легковесная библиотека для генерации уникальных идентификаторов.
- **Magic String** – Библиотека для манипуляции строками JavaScript без изменения их исходного содержания.
- **CSSType** – Пакет для работы с типами CSS в **TypeScript**.
- **Picocolors** – Минималистичная библиотека для работы с цветами в консоли.
- **Source-map-js** – Библиотека для работы с **source maps** в JavaScript.
- **Entities** – Пакет для работы с HTML-сущностями .
- **Entree-walker** – Библиотека для обхода структуры данных.

## 💻 Разработка и тестирование
Для удобства разработки и тестирования используются различные инструменты и настройки:

- VS Code – Редактор кода, для которого предусмотрены настройки в .vscode/.
- Jest – Для тестирования различных компонентов и логики приложения.
- Babel – Для транспиляции JavaScript с использованием новейших стандартов ECMAScript.
- PostCSS – Для обработки и оптимизации CSS файлов.



## 📌 Установка
1. Клонируйте репозиторий:
```bash
git clone https://github.com/uichyi/webProject.git](https://github.com/FixSad/webrazr.git
```
2. Для удобства после клонирования гита, открыть 2 окна VScode:
    в одном открыть django-back, во втором открытьme-vue-app
   
3.1. Перейдите в директории проекта django-back:
```bash
cd backend
```
4.1. Установите нужные библиотеки:
```bash
pip install 
```
3.2. Перейдите в директории проекта my-vue-app и установите нужные библиотеки:
```
npm install 
``` 

## ▶ Запуск проекта django-back
```
cd backeng
python manage.py runserver
```
## ▶ Запуск проекта my-vue-app
```
npm run server
```

Чтобы сбилдить .vue файлы нужно во фронте проекта запустить команды 
```bash
npm install
npm update
npm run build
```
После этого создастся папка dist в которой будет файлы
Эти файлы нужно перенести в папку static django-back проекта (предварительно очистив её)
