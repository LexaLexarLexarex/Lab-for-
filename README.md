# Lab-for-
Лабораторная работа №1.
Выполнили студенты 19se-1: Долгополов и Бурцев (Долгобурцев)

ВАРИАНТ 3.
Уровень 1
1. Дана схема базы данных в виде следующих отношений. С помощью операторов SQL создать логическую структуру соответствующих таблиц для хранения в СУБД, используя известные средства поддержания целостности (NOT NULL, UNIQUE, и т.д.). Обосновать выбор типов данных и используемые средства поддержания целостности. При выборе подходящих типов данных использовать информацию о конкретных значениях полей БД (см. прил.1)

![image](https://user-images.githubusercontent.com/62442582/114885624-80f26780-9e0f-11eb-8189-3c8bedd96d8b.png)

2. Ввести в ранее созданные таблицы конкретные данные (см. прил. 1). Использовать скрипт-файл из операторов INSERT или вспомогательную утилиту .

![image](https://user-images.githubusercontent.com/62442582/114889477-d3815300-9e12-11eb-8f11-8f03920036af.png)

3. Используя оператор SELECT создать запрос для вывода всех строк каждой таблицы. Проверить правильность ввода. При необходимости произвести коррекцию значений операторами INSERT, UPDATE, DELETE.

![image](https://user-images.githubusercontent.com/62442582/114909242-996d7c80-9e25-11eb-8eb1-f9cd1efd68d4.png)

![image](https://user-images.githubusercontent.com/62442582/114909730-e3eef900-9e25-11eb-9cc7-b0fb027b3aa4.png)
![image](https://user-images.githubusercontent.com/62442582/114909963-fe28d700-9e25-11eb-8c58-dc632000ed0e.png)
![image](https://user-images.githubusercontent.com/62442582/114910038-14cf2e00-9e26-11eb-9cd5-dfd93ac04a9d.png)
![image](https://user-images.githubusercontent.com/62442582/114910124-30d2cf80-9e26-11eb-88b4-58cbe0d1505c.png)

4. Создать запросы для вывода:
a) всех различных фамилий заказчиков и размеров их скидок;
![image](https://user-images.githubusercontent.com/62442582/114910441-97f08400-9e26-11eb-8d52-5421607fd146.png)
![image](https://user-images.githubusercontent.com/62442582/114910501-a50d7300-9e26-11eb-8e08-a10fe3d8ef2e.png)

b) всех различных районов проживания заказчиков;
![image](https://user-images.githubusercontent.com/62442582/114910631-ccfcd680-9e26-11eb-9f69-8c9ff1e20c8e.png)
![image](https://user-images.githubusercontent.com/62442582/114910671-d7b76b80-9e26-11eb-8d06-376752bae517.png)

c) всех названий прокатных пунктов и их мест расположения.
![image](https://user-images.githubusercontent.com/62442582/114910891-15b48f80-9e27-11eb-9087-c5ee82bd6473.png)
![image](https://user-images.githubusercontent.com/62442582/114910917-1fd68e00-9e27-11eb-95e3-f58c7be24dea.png)


5. Создав запрос получить следующую информацию:

a) идентификаторы и фамилии заказчиков, проживающих в Приокском или Сормовском районе или тех, чьи фамилии оканчиваются на “ин”;
![image](https://user-images.githubusercontent.com/62442582/114911979-274a6700-9e28-11eb-80e7-30a98ebb3994.png)
![image](https://user-images.githubusercontent.com/62442582/114912042-36311980-9e28-11eb-9471-c713ca1df073.png)

b) номер, дата, срок проката и сумма для тех записей, где сумма проката более 2000руб. Отсортировать по возрастанию суммы и срока проката;
![image](https://user-images.githubusercontent.com/62442582/114913099-780e8f80-9e29-11eb-80df-1ad456997433.png)
![image](https://user-images.githubusercontent.com/62442582/114913132-8361bb00-9e29-11eb-9b7b-89490dd93be8.png)

c) названия вещей и адрес складирования, для вещей, оставшихся в количестве не менее 7.
![image](https://user-images.githubusercontent.com/62442582/114913680-26b2d000-9e2a-11eb-9779-648b9c3382d7.png)
![image](https://user-images.githubusercontent.com/62442582/114913710-2fa3a180-9e2a-11eb-943e-3482a753d972.png)

6. На основании данных о прокате вещей вывести все данные в таком формате:

a) фамилия клиента, название пункта проката, дата, номер прокатной квитанции. Отсортировать по первым двум полям;
![image](https://user-images.githubusercontent.com/62442582/114917720-eefa5700-9e2e-11eb-91b1-19242c47267f.png)
![image](https://user-images.githubusercontent.com/62442582/114917770-fd487300-9e2e-11eb-8edb-9e56c33a878c.png)

b) название пункта проката, дата, название вещи, сумма.
![image](https://user-images.githubusercontent.com/62442582/114918414-b9a23900-9e2f-11eb-9674-6f28ec15fb86.png)
![image](https://user-images.githubusercontent.com/62442582/114918466-c6bf2800-9e2f-11eb-80f3-2c70a7a5522e.png)

7. Вывести:

a) названия прокатных пунктов, которые отдавали в прокат утюги или оказывали услуги клиентам своего района;
![image](https://user-images.githubusercontent.com/62442582/115962078-39ac5b00-a522-11eb-887e-088b6316b566.png)
![image](https://user-images.githubusercontent.com/62442582/115962087-4b8dfe00-a522-11eb-8951-b86aa622de6d.png)

b) имена и адреса заказчиков, бравших в прокат вещи со стоимостью проката более 8000руб не ранее февраля месяца. Вывести вместе с названиями прокатных пунктов, где были взяты вещи, проиведя по ним сортировку;
![image](https://user-images.githubusercontent.com/62442582/115962258-21890b80-a523-11eb-92fd-3e0aa78c190c.png)
![image](https://user-images.githubusercontent.com/62442582/115962266-2c43a080-a523-11eb-9238-e149c8ce263b.png)

c) название и прокатную цену вещей взятых заказчиком Кожаковым в прокатных пунктах других районов;
![image](https://user-images.githubusercontent.com/62442582/115962400-e3401c00-a523-11eb-8d18-da5f4e792719.png)
![image](https://user-images.githubusercontent.com/62442582/115962405-ec30ed80-a523-11eb-8188-4420e77faa03.png)

d) название и оставшееся количество вещей, которые отдавали более чем в одном прокатном пункте.
![image](https://user-images.githubusercontent.com/62442582/115962510-6c575300-a524-11eb-8c2a-77b717a51477.png)
![image](https://user-images.githubusercontent.com/62442582/115962518-724d3400-a524-11eb-8e54-1b9c3dfea737.png)

8. Создать запрос для модификации всех значений столбца с суммарной величиной оплаты таблицы прокат, чтобы он содержал истинную сумму, оплачиваемую клиентом ( с учетом скидки). Вывести новые значения.
  ![image](https://user-images.githubusercontent.com/62442582/114924492-bc545c80-9e36-11eb-96ea-91643658ba04.png)

  ![image](https://user-images.githubusercontent.com/62442582/114924447-acd51380-9e36-11eb-9114-e3f997b8308b.png)

9. Расширить таблицу с данными о прокате столбцом, содержащим величину взимаемых комиссионых. Создать запрос для ввода конкретных значений во все строки таблицы проката.
  ![image](https://user-images.githubusercontent.com/62442582/114926768-6a610600-9e39-11eb-8109-e0a241f41788.png)
  ![image](https://user-images.githubusercontent.com/62442582/114926795-70ef7d80-9e39-11eb-8c6b-4f2bfb6c15c1.png)

Уровень 2

10. Используя операцию IN (NOT IN) реализовать следующие запросы:

a) найти вещи, бравшиеся в прокат заказчиками с размером скидки более 2%;
![image](https://user-images.githubusercontent.com/62442582/115472448-8a7e3400-a242-11eb-90d1-bbe7ecd03718.png)
![image](https://user-images.githubusercontent.com/62442582/115472466-9669f600-a242-11eb-9629-e65ecec8e69c.png)

b) найти все вещи, бравшиеся в прокат заказчиком, бравшим что-либо в прокатных пунктах своего района;
![image](https://user-images.githubusercontent.com/62442582/115912673-4b392880-a478-11eb-9f84-a117a830a111.png)
![image](https://user-images.githubusercontent.com/62442582/115912642-3f4d6680-a478-11eb-9b99-56e018ad4c46.png)

c) запросы заданий 7.b, 7.с.

11. Используя операции ALL-ANY реализовать следующие запросы:

a) определить те вещи, которые брались летом на самый продолжительный срок;
![image](https://user-images.githubusercontent.com/62442582/115962608-ed164f00-a524-11eb-8553-362020366127.png)
![image](https://user-images.githubusercontent.com/62442582/115962623-f8697a80-a524-11eb-9c0b-a756bf0b87b9.png)

b) найти прокатные пункты, отдававшие вещи с самой большой ценой;
![image](https://user-images.githubusercontent.com/62442582/115962697-48e0d800-a525-11eb-9872-ada09c705303.png)
![image](https://user-images.githubusercontent.com/62442582/115962709-539b6d00-a525-11eb-9869-7482d8085599.png)

c) найти таких заказчиков, которые имеют такой же размер скидки, как кто-либо из бравших на прокат радиоприемник;
![image](https://user-images.githubusercontent.com/62442582/115962771-8d6c7380-a525-11eb-8ba9-1f6fd35879a0.png)
![image](https://user-images.githubusercontent.com/62442582/115962779-965d4500-a525-11eb-9882-4a9b39c14b29.png)

d) запрос задания 7.а.
![image](https://user-images.githubusercontent.com/62442582/115962877-0ff53300-a526-11eb-97b5-4e2a58d63771.png)
![image](https://user-images.githubusercontent.com/62442582/115962888-1d122200-a526-11eb-8de7-35c0d82bc061.png)

12. Используя операцию UNION получить адреса проживания заказчиков и места расположения прокатных пунктов.
![image](https://user-images.githubusercontent.com/62442582/115962944-3fa43b00-a526-11eb-8484-b4df71e89ab0.png)
![image](https://user-images.githubusercontent.com/62442582/115962949-4af76680-a526-11eb-853c-50e19009ad43.png)

13. Используя операцию EXISTS ( NOT EXISTS ) реализовать нижеследующие запросы. В случае, если для текущего состояния БД запрос будет выдавать пустое множество строк, требуется указать какие добавления в БД необходимо провести.

a) найти две самые дорогие вещи, сдававшиеся в прокат не позднее октября;
![image](https://user-images.githubusercontent.com/62442582/115963023-9dd11e00-a526-11eb-858d-e47d5f3ec90a.png)
![image](https://user-images.githubusercontent.com/62442582/115963031-a9244980-a526-11eb-95e5-05ac47883b80.png)

b) найти прокатные пункты, сдававшие все вещи всем заказчикам из Нижегородского района;
![image](https://user-images.githubusercontent.com/62442582/115963103-fa343d80-a526-11eb-9662-43b74a9b2eaa.png)
![image](https://user-images.githubusercontent.com/62442582/115963114-028c7880-a527-11eb-9c45-8c65477884d9.png)

c) найти заказчиков не бравших в прокат вещи ценой мене 5000руб. в прокатных пунктах чужих районов;

d) найти заказчиков, бравших вещи во всех прокатных пунктах с размером комиссионных менее 5%.

14. Реализовать запросы с использованием аггрегатных функций:

a) найти средний срок проката вещей, бравшихся в прокатных пунктах Советского района;
![image](https://user-images.githubusercontent.com/62442582/115992081-6caf2700-a5d4-11eb-848c-e9d9da1643cb.png)
![image](https://user-images.githubusercontent.com/62442582/115992092-76d12580-a5d4-11eb-9ee0-fd96666db20d.png)

b) найти заказчика, имеющего минимальную скидку среди бравших вещи в бюро проката N8;

c) найти те записи о прокате, где стоимость проката больше средней по району, в котором располагается бюро найма;

d) найти общее число вещей, бравшихся Семеновым.

15. Используя средства группировки реализовать следующие запросы:

a) найти суммарную величину стоимости проката для каждой вещи;
![image](https://user-images.githubusercontent.com/62442582/115963281-4ed7b880-a527-11eb-9a00-5bcd86a87ff1.png)
![image](https://user-images.githubusercontent.com/62442582/115963288-572ff380-a527-11eb-9bdb-13ced8e6e575.png)

b) определить для каждой вещи средний срок проката за осенний период;

c) найти для каждого заказчика, бравшего вещи во всех бюро проката Советского района, число различных бравшихся в прокат вещей;

d) получить сводную таблицу “бюро проката - вещь-суммарная стоимость проката”.
