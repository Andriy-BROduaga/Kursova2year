ТЕМА Планування робочого дня
Федірко Андрій - ІПЗ-24
Посилання на структуру
https://dbdiagram.io/d/656096fb3be1495787aab750 

Цього разу думаю структура так і залишиться, по можливих питаннях:
1) таблиця Statistic - зберігає в собі дані про успішність вионання завдань кожного співробітника, загальний робочий час за день, в майбутньому можливо ще щось
2) таблиця Task зберігає в собі всі завдання, які були виконані, виконуються, або не виконані.
3) Category_of_Task таблиця створена для зберігання типів завдань для подального розподілення завдань по співробітниках, щоб не охарактеризовувати кожне завдання в таблиці Task
4) Таблиця Job створена для кращого розподілення завдань, наприклад для студентів завданням буде здати лабораторну роботу, а для декана - узгодити розклад
5) Person_data дані - на кожну особу
6) Plan_of_the_day - план робочого дня. Включає в себе кількість завдання, їх статус (виконані чи ні), і орієнтовний час виконання завдань
7) Template_plan - шаблонний план для певної посади. Включає графік роботи, і в майбутеьому особливості кожної професії

