# todo
Мій todo list в node.js (express) і mongoDB.

Want to implement basic authentication. Later authentication using facebook/github/google oauth. And with that implemented even try to implement my own oauth2 authentication.

На Todolist можна зберігати списки справ. Список має ім'я, він може містити перелік завдань, які об'єднані, наприклад, спільною метою або проектом. Кожне завдання або список містять не тільки назва, а й короткий опис, за допомогою якого можна, наприклад, уточнити призначення завдання або списку, нагадати про особливо важливих моментах.

Завдання в списку можна переміщати просто за допомогою миші - перетягуючи завдання в потрібне місце списку, можна таким чином перебудовувати список так, як зручно користувачеві. Окремі пункти списку можна редагувати, встановлюючи, наприклад, дату завершення завдання.

Ще одна корисна функція сервісу - спільний доступ до списку. Встановити її можна в розділі «Загальний доступ», просто позначивши відповідний значок. В результаті за спеціальним коротким адресою всі бажаючі зможуть переглядати список.

Tasks can have deadlines, priority, predicted time to accomplish, defined project, real time to accomplish, done/in progress/blocked/not started. Task can have tags and special requirements. 

Statistics for tags, projects. Predicted time and real time in minutes/pomodoros.
Statistic for each day. How productive day was.

Listing todos according to priority, deadlines, status, size, tags, proejcts, special requirements.

Lucky task. Select task according to priority/deadline/predicted time. Available some skips.

Generating .xls with tasks and time spend on them on each month for contract.

First part:
REST API for todos

Second part:
Progressive web app. Use modernizr, service worker, push notifications.

Additions:
Pomodoro timer.

Technologies i want to learn by doing this project:
- configure nice gulp file for this apps (SASS etc.)
- use webpack for client side js
- babel for ES6
- create basic yo generator for similar apps
- swig for templates
- configure linters for VS Code
- tests with Tape
- sails as nice node.js framework for app/ express for api
- postman for testing API
- check bower

Other cool tools for another projects:
- metalsmith as ssg
- keystoneJS as cms
