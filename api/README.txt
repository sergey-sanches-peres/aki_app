Команда для запуска api: npm run dev

Чтобы протестировать api, можно послать запрос http://localhost:3003/test или http://localhost:3003/test/testsecond

Для установки зависимостей использовать @types/название_модуля. Пример: npm install --save @types/node. Это нужно для того, чтобы типизировать модули, написанные на JS.
Но если модуль встал неправильно, то можно попробовать установить второй раз, но уже без @types/название_модуля.

Пояснение за строение src:
-controllers   - контроллеры, принимают запросы и отдают ответы.
-services      - сервисы, делают всякую логику с данными прежде чем запросить/ответить.
-repositories  - репозитории, обращаются к БД.
-routes        - навигация запросов к api.

Обращение к Ивану:
    "Разумеется ты можешь смело всё менять так, как тебе удобно. Я предоставил свою сборку и настройку серверной части, которая на мой взгляд упрощает работу"