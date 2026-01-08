# ai_news
An app for daily searching of news, job vacancies, and articles, with automatic publishing to Telegram

## stages

I. **get raw data**:

1. Выбираем из файла записанные id
2. Идём на HH, получаем по запросу данные
3. Получаем новые id:
4. Выбираем интересующие поля
5. Идём на страницу вакансии, по значению атрибута через XPAth получаем полное описание
6. Все данные записываем в файл

II. **get all pages**