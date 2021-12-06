# SmartApp Backend

MAIN

Это backend на SmartApp Code для небольшого Canvas App: Todo (добавление, выполнение и удаление задач. [См. видео](https://youtu.be/P-o2rwHhARo)). Для работы необходимо сделать fork-проекта в свой git-репозиторий, создать новый проект в SmartApp Studio и подключить к нему созданный git-репозиторий. После этого можно взять токен и связать backend с [frontend](https://github.com/sberdevices/todo-canvas-app). 


## Создание проекта в "SmartApp Code":
1. Делаем fork проекта в свой репозиторий;
1. Идём на страницу SmartApp Code ([ссылка](https://smartapp-code.sberdevices.ru/));
1. Нажимаем "Создать проект";
1. Указываем "Имя";
1. Переходим в раздел "Размещение";
1. Указываем внешний репозиторий;
1. Указываем ссылку до созданного репозитория, бранч main;
1. Указываем доступ: собственная учётная запись, логин и пароль от учётной записи в github;
1. Нажимаем "Создать";
1. Нажимаем "Создать смартапп";
1. Переходим в раздел разработка.
1. Нажимаем "Сценарии";
1. Нажимаем "Собрать";
1. Нажимаем "Публикации";
1. Нажимаем "Получить вебхук" (URL на Webhook копируется в буфере обмена).

## Заводим проект в "SmartApp Studio":

1. Идём на страницу SmartApp Studio ([ссылка](https://smartapp-studio.sberdevices.ru/));
1. Нажимаем "Создать смартапп";
1. Указываем "Имя";
1. Переключаем "Выбор типа смартапа" на "Canvas App";
1. Переключаем "Выбор инструмента" на "Есть готовое приложение";
1. Указываем URL на "Webhook" (полученный в "SmartApp Code");
1. Указываем URL на "Frontend Endpoint" (url страницы, где будет размещаться клиентская часть вашего приложения. Для локального запуска не используется, можете указать любой);
1. Нажимаем "Создать смартап".
