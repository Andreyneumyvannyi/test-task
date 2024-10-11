# Доска управления задачами

## Технологический стек
- Используйте React (только хуки, без классов).
- Typescript обязателен.
- Управление состоянием реализуйте с помощью стейт менеджера (Redux, Redux Toolkit, Zustand).
- Для хранения данных используйте возможности браузера, но если вы можете реализовать бэкенд или знаете сторонние сервисы, мы это оценим.
- Вам разрешено использовать фреймворки (например, NextJS).
> Требования к стеку, указанные выше, обязательны к соблюдению. Вы можете использовать любые библиотеки.

## Требования
1. Каждый пользователь может создавать/обновлять/удалять задачи (реализовать UX/UI самостоятельно). Желательно использовать библиотеку UI компонентов, например, AntDesign.
2. Доска должна содержать 3 столбца — «Задачи», «В процессе», «Готово».
3. Каждый пользователь должен иметь возможность добавлять/обновлять/удалять карточки. Реализовать на отдельной странице, удаление должно сопровождаться всплывающим модальным окном для подтверждения. В этом окне должна быть информациия об удаляемой задаче.
4. Когда пользователь создает или редактирует задачу форма должна валидироваться. Не допускаются пустые поля для отправки.
6. Для каждой задачи должна быть реализована возможность изменить статус. Можно реализовать как перетаскиванием задач в соответствующие столбцы, так и добавлением переключателя в саму карточку.
7. Можно найти задачу в поиске. 
> Аутентификация пользователя не требуется.

## Оценка

Что мы будем оценивать:
- работоспособность: как работает ваше приложение;
- структура проекта: как вы структурируете свои файлы;
- качество кода: как вы пишете чистый, читаемый код (не стесняйтесь устанавливать и использовать ESLint, Stylelint и Prettier);
- знание технологий и их экосистемы: как вы используете библиотеки;
- тестирование: как можно протестировать свой код;

## Макеты
![1](https://github.com/user-attachments/assets/c54224a2-f8dd-4614-9ac7-6001c51172e5)
![2](https://github.com/user-attachments/assets/a20b292a-d3ae-4dcf-9eb1-1fa0c81ed511)



## Как выполнить задание
- создать новый публичный репозиторий на GitHub;
- разработать приложение в соответствии с требованиями;
- отправьте нам ссылку на ваш репозиторий;
- разверните свое приложение на любом сервисе;
- если вы чего-то не видите в дизайне, вы можете реализовать эту функциональность в пользовательском интерфейсе, просто опираясь на свое видение и понимание.
