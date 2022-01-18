# Бэкенд проекта Место 
### *Учебный проект от [Яндекс.Практикум](https://practicum.yandex.ru/web/)*

## Описание проекта
Место - это интерактивная страница, на которой пользователи могут делиться фотографиями, удалять их и ставить лайки. 

Данный учебный проект создан в рамках прохождения 4-13 спринтов курса Веб-разработчик. Цель проекта закрепить на практике пройденный учебный материал, в который входят:

- Взаимодействие с Express и MongoDB;
- Описания схем и моделей;
- Описания контроллеров и роутов;
- CORS. Обработка ошибок.

## Функционал:
- Роуты для пользователей:
  - GET /users — возвращает всех пользователей из базы;
  - GET /users/:userId — возвращает пользователя по _id;
  - POST /users — создаёт пользователя с переданными в теле запроса name, about и avatar.

- Роуты для карточек:
  - GET /cards — возвращает все карточки из базы;
  - POST /cards — создаёт карточку с переданными в теле запроса name и link, устанавливает поле owner для карточки;
  - DELETE /cards/:cardId — удаляет карточку по _id.

## Стек технологий:
- JavaScript:
  - Промисы (Promise);
  - Асинхронность и оптимизация;
  - Rest API;
- Node.js;
- Express;
- MongoDB.

## Директории
* `/controllers` – содержит файлы описания моделей пользователя и карточки;
* `/models` – содержит файлы описания схем пользователя и карточки;
* `/routes` — содержит описание основных роутов для пользователя и карточки;
* `/utils` – содержит описание ошибок.

## Установка и запуск проекта:
Клонировать репозиторий:

    git clone https://github.com/ia-stepanov/express-mesto.git

Установить зависимости:

    npm install

Запустить сервер:

    npm run start

Запустить сервер с hot-reload:

    npm run dev

## Языки:
- JavaScript

## Библиотеки:
- Express

## База данных:
- MongoDB

## Макеты Проектной работы в Figma:
- [Макет 4](https://www.figma.com/file/2cn9N9jSkmxD84oJik7xL7/JavaScript.-Sprint-4);
- [Макет 5](https://www.figma.com/file/bjyvbKKJN2naO0ucURl2Z0/JavaScript.-Sprint-5);
- [Макет 6-7](https://www.figma.com/file/kRVLKwYG3d1HGLvh7JFWRT/JavaScript.-Sprint-6);
- [Макет 9](https://www.figma.com/file/PSdQFRHoxXJFs2FH8IXViF/JavaScript-9-sprint);
- [Макет 12](https://www.figma.com/file/5H3gsn5lIGPwzBPby9jAOo/JavaScript.-Sprint-12).

## Чеклисты Проектной работы:
- [Чеклист 4](https://code.s3.yandex.net/web-developer/checklists/new-program/checklist-4/index.html);
- [Чеклист 5](https://code.s3.yandex.net/web-developer/checklists/new-program/checklist-5/index.html);
- [Чеклист 6](https://code.s3.yandex.net/web-developer/checklists/new-program/checklist-6/index.html);
- [Чеклист 7](https://code.s3.yandex.net/web-developer/checklists/new-program/checklist-7/index.html);
- [Чеклист 8](https://code.s3.yandex.net/web-developer/checklists/new-program/checklist-8/index.html);
- [Чеклист 9](https://code.s3.yandex.net/web-developer/checklists/new-program/checklist-9/index.html);
- [Чеклист 10](https://code.s3.yandex.net/web-developer/checklists/new-program/checklist-10/index.html);
- [Чеклист 11](https://code.s3.yandex.net/web-developer/checklists/new-program/checklist-11/index.html);
- [Чеклист 12](https://code.s3.yandex.net/web-developer/checklists/new-program/checklist-12/index.html);
- [Чеклист 13](https://code.s3.yandex.net/web-developer/checklists/new-program/checklist-13/index.html).

## Место на JS:
https://github.com/ia-stepanov/mesto

## Место на «React»:
https://github.com/ia-stepanov/react-mesto-auth
