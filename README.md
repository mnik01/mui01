# Пайплайн для билда и пуша в npm:

- Коммитим изменения ```git commit```
- Поднимаем версию библиотеки ```npm version patch```
- Билдим ```npm run build```
- Копировать package.json и lib/src в dist/ удалить index.js index.map.js
- Публикуем типизированную сбилженую версию в npm ```npm publish dist```

# TODO: Перенести на CI/CD пайплайн



# Поднять локально:
- ```npm run build```
