# recommendation_system
An integrated approach to solving business problem.

##Цель проекта: 

>Подготовить основу рекомендательной системы для онлайн-школы MasterMind  
---
## Задача проекта: 
>Разработать рекомендательную систему, с помощью которой можно будет предлагать клиентам интересные им курсы с целью повышения среднего чека.
### ФОРМАЛИЗОВАННЫЕ ЗАДАЧИ
--- 
1. **Подготовить данные с помощью SQL** 

2. **Обработать данные средствами Python.**  

3. **Составить итоговую таблицу с рекомендациями, снабдив её необходимыми комментариями.** 
---
## Описание данных #
 Проектный анализ будет проводиться на данных онлайн-школы ***MasterMind*** 
 
 Анализ будет выполняться на основе данных пользователей, которые совершали покупки за ***2017-2018 год***.  
 ## Используемые датасеты: 
---
***Таблица carts*** - данные о пользовательских корзинах

| Название поля      | Описание                | 
| :------------- |:------------------|
| Promo Code ID     |ID промокода, если он есть | 
| Purchased At    |дата оплаты  |  
| User ID |  ID пользователя | 
| Created At  | дата создания корзины |
| Updated At  | дата последнего обновления информации |
| ID | идентификатор корзины  | 
|State| состояние оплаты|


***Таблица cart items*** — данные о курсах, которые пользователи добавили в корзину 

| Название поля      | Описание                | 
| :------------- |:------------------|
| Created At | дата создания события  |
|Resource Type|тип продукта|
|Resource ID |ID курса |
|Cart ID|идентификатор корзины |
|Updated At |дата последнего обновления информации |
|ID|идентификатор операции|
