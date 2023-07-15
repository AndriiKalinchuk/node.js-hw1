nodejs-hw-01

# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list" - https://monosnap.com/file/Va7Fp6l35J7lrwGQu0vfmjIH2EcbAI

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6 - https://monosnap.com/file/p6K6Gnfhugjndqx7Ui0yKraSsisw87

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22 - https://monosnap.com/file/ceBqwlJyKgsvJzHUyGnDOXNNli7Eua

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.

node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH - https://monosnap.com/file/gC0bRubrLlHeVuaoolwiaSoGmWa8jM
