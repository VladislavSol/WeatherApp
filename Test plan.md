# План тестирования
---

# Содержание
1 [Введение](#intro)  
2 [Атрибуты качества](#quality)  
3 [Аспекты тестирования](#features)  
4 [Подходы к тестированию](#approach)  
5 [Представление результатов](#pass)  
6 [Выводы](#conclusion)

<a name="intro"/>

## Введение

Данный документ описывает план тестирования приложения ["WeatherApp"](https://github.com/VladislavSol/WeatherApp/). Документ предназначен для людей, выполняющих тестирование данного проекта. Цель тестирования - проверка соответствия реального поведения программы проекта и ее ожидаемого поведения, которое описано в [требованиях](https://github.com/VladislavSol/WeatherApp/blob/main/Requirements%20/Requirements_Document.md).

<a name="quality"/>

## Атрибуты качества

1. Функциональность:
    - функциональная полнота: приложение должно выполнять все заявленные функции;
    - функциональная корректность: приложение должно выполнять все заявленные функции корректно;

<a name="features"/>

## Аспекты тестирования

В ходе тестирования планируется проверить реализацию основных функций приложения. Аспекты, подвергаемые тестированию: 
* Запуск приложения;      
* Переход на главную страницу;    
* Переход на страницу выбора города;    
* Добавление/удаление городов на странице выбора города;    
* Уведомление о состоянии Интернет-соединения.    

### Запуск приложения
Этот вариант использования небходимо протестировать на:
* запуск приложения;
* отображение окна приложения согласно [мокапу](https://github.com/VladislavSol/WeatherApp/blob/main/Mockups/logo.png).

### Переход на главную страницу   
Этот вариант использования небходимо протестировать на:
* переход на главную страницу;
* отображение окна приложения согласно [мокапу](https://github.com/VladislavSol/WeatherApp/blob/main/Mockups/main.png).

### Переход на страницу выбора города   
Этот вариант использования небходимо протестировать на:
* переход на страницу выбора города;
* отображение окна приложения согласно [мокапу](https://github.com/VladislavSol/WeatherApp/blob/main/Mockups/setCity.png).

### Добавление/удаление городов на странице выбора города    
Этот вариант использования небходимо протестировать на:
* добавление нового города в список;
* удаление города из списка.

### Уведомление о состоянии Интернет-соединения. 
Этот вариант использования небходимо протестировать на:
* отображение уведомления об отсутствии Интернет-соединения с сервером.

<a name="approach"/>

## Подходы к тестированию

При тестировании будет использован ручной подход.

<a name="pass"/>

## Представление результатов

Результаты представлены в документе ["Результаты тестирования"](https://github.com/VladislavSol/WeatherApp/blob/main/Test%20result.md).

<a name="conclusion"/>

## Выводы

Данный тестовый план позволяет протестировать основной функционал приложения. Успешное прохождение всех тестов не гарантирует полной работоспособности на всех версиях платформ и архитектурах, однако позволяет полагать, что данное программное обеспечение работает корректно.
