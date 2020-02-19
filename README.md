# Завдання програми – менеджмент книжками.
### У програмі реалізовані такі функції як:
1. Зчитування книжок з текстового файлу
1. Добавлення книжки.
1. Вставка книжки на вказаний користувачем програми індекс.
1. Сортування всіх книжок
1. Видалення книжок з ціною, нижчою за середню.
1. Вивести список з урахуванням усіх змін(якщо вони вже були здійснені).
1. Зберегти книжки у текстовий файл з урахуванням змін.

Для зручності користуванням ПЗ було розроблено меню з усіма вище перерахованими пунктами, яке виводиться після кожної дії. Вивід даних зроблено так,щоб користувачу не складало складності знайти те, що йому потрібно.

ПЗ зроблено так, щоб про будь-яку помилку(помилковий ввід даних, не правильний запис у файл) користувач сповіщений з програми, тобто ніяка помилка не перерве виконання і програма поводитиметься належним чином.

Для вибору пункту з меню користувачу просто потрібно ввести номер пункту та натиснути на «Enter». Далі, залежно від вибраного пункту, користувач або переглядає виведені дані, або повинен щось ввести. Все, що користувач повинен робити програма вказує та у разі помилки вводу сповіщає про неї.
Перезаписати файл або змінити якісь дані у ньому можна відкривши файл data.txt у папці проекту.
Всі дані у файл потрібно записувати лише через пробіл. Також варто вводити кожну нову книжку з нового рядку. У разі помилкового запису у файл програма дасть вам знати, що у файлі помилку з книжкою(вкажить її порядковий номер) і вона не може її прочитати.
Програма сортує книжки за ціною, щоб користувач міг чітко  бачити список книг від найдорожчої до найдешевшої. Також при потребі користувач може видалити всі книжки з ціною, яка нижча за середню.
###Важливо: 
Всі зміни, впровадженні в процесі виконання програми потрібно зберегти, тобто перед закриттям програми потрібно здійснити пункт меню №7, інакше всі зміни будуть втрачені і зміст файлу буде таким, як і до виконання програми.