# Тестовые задания

## img_grab
#### Постановка задачи
Написать скрипт, который принимает в качестве параметра адрес страницы и скачивает все изображения с нее.

С помощью гема Mechanize скрипт разбирает страницу и вытаскивает все изображения из нее.
Массив изображений проверяется на уникальность и разбивается на подмассивы, которые передаются отдельному потоку.
Каждый поток скачивает переданное ему изображение.

## choice_obj
#### Постановка задачи
В памяти есть 10 000 000 объектов со следующими полями: 
1) возраст (0..100) 
2) зарплата (0..1000000,0) 
3) рост (0..200) 
4) вес (0..200) 
Нужно написать максимально быстрый алгоритм для выбора объектов по определнным условиям (условий может быть от 0 до 4, в качестве условия можно указать диапазон значений)