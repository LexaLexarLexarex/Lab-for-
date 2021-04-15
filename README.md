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
