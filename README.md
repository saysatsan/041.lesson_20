# 041.lesson_20

## The project was deployed on the GitHub page using the [link](https://saysatsan.github.io/041.lesson_20/)

##TASK
Вивести список символів у вигляді таблиці.

Ви можете створити таблиці самостійно на сайті:

https://mockapi.io/projects

Приклад об’єкта ресурсу для «heroes» (шлях має бути «heroes»):

{
  "name": "Залізна людина",
  "comics": "Марвел",
  "улюблений": правда,
  "id": "1"
}
Приклад об'єкта ресурсу для "всесвітів":

{
  "id": "1",
  "name": "Marvel"
}
Таблиця складається з 4 колонок:

Ім'я прізвище
Комікси (DC, Marvel, Comix Zone)
Вибране (прапорець)
Дії (кнопка Видалити)
Над таблицею є форма з трьома полями для додавання нового символу:

Ім'я Прізвище (введення)
Комікси (DC, Marvel, Comix Zone) (вибрати) – дані отримані за допомогою методу GET із ресурсу "всесвіти"
Вибране (true, false) (прапорець)
Дії:

Після надсилання форми персонаж додається до бази даних (POST), а інформація про героя відображається в рядку HTML у таблиці. Якщо герой із такою ж властивістю «ім’я» вже існує в базі даних, об’єкт не додається до бази даних (ви можете просто записати повідомлення на консоль про те, що користувач із таким ім’ям уже існує в базі даних).
Коли стан прапорця в стовпці «Вибране» змінюється, дані для цього персонажа оновлюються в базі даних (PUT).
Після натискання кнопки Видалити в рядку персонажа відповідний герой видаляється з бази даних (DELETE), а відповідний <tr>елемент – із таблиці.
Базовий макет надається у вкладеному архіві "heroes.zip".
