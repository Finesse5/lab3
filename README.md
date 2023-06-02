# Laba3
В этой лабараторной работе было создано приложение, которое из формы на сайте создает таблицу на том же сайте

Был использован паттерн программирования MVC
Model - Student.java
View - index.jsp
Controller - StudentController.java

На сайте вводятся данные:
![image](https://github.com/Finesse5/lab3/assets/127689665/3c592cce-d323-4d9c-b969-42762e7aeb80)


Из данных создается json строчка
Эта строчка дессериализуется в POJO объект и так записывается в файл на сервере 

И выводятся в табличку под формой ввода
![image](https://github.com/Finesse5/lab3/assets/127689665/80e55d03-049e-4f5b-a9a4-a814279d186d)

