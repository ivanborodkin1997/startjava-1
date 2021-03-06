# Занятие второе

## Разбор домашнего задания
- ![video](https://user-images.githubusercontent.com/29703461/81983788-359a6c80-9634-11ea-9b47-09a56fd3d999.png) [Калькулятор](https://drive.google.com/file/d/1VXg-RlS-DprXOjbH8s5FieOUga_PCzBZ/view?usp=sharing)
- ![video](https://user-images.githubusercontent.com/29703461/81983788-359a6c80-9634-11ea-9b47-09a56fd3d999.png) [Угадай число](https://drive.google.com/file/d/1XFSXQuUchrwD7aNsUQKjxvRtKNy1_wkx/view?usp=sharing)
- ![video](https://user-images.githubusercontent.com/29703461/81983788-359a6c80-9634-11ea-9b47-09a56fd3d999.png) [Символы Unicode](https://drive.google.com/file/d/1CSYppASCuuIGUm9SBVCDR0d4nodhLqFq/view?usp=sharing)

## Темы занятия
1. [Что такое ООП](#1)
1. [Что такое класс](#2)
1. [Что такое объект](#3)
1. [Инкапсуляция: геттеры/сеттеры](#4)
1. [Ответы на вопросы](#5)
1. [Домашнее задание](#6)

## ![video](https://user-images.githubusercontent.com/29703461/81982928-d556fb00-9632-11ea-9794-ea198832d674.png) 1. <a name="1">[Что такое ООП](https://drive.google.com/file/d/1Jsfz5Ygb5Ct1in7MTcNV3wSsx_30D5h3/view?usp=sharing)</a>

>ООП — это одна из парадигм (методологий, способов оформления кода) программирования, основанная на принципах, предполагающих написание программного кода в виде классов и их объектов, взаимодействующих друг с другом

**Материалы:**
- [Объектно-ориентированное программирование](https://ru.wikipedia.org/wiki/Объектно-ориентированное_программирование) (wiki)
- ООП с примерами. Часть [1](https://habr.com/post/87119/), [2](https://habr.com/post/87205/)
- [Зачем нам ООП и что это такое](https://habr.com/post/148015/)
- [Объектно-ориентированное программирование](http://info.javarush.ru/translation/2016/01/28/Объектно-ориентированное-программирование-перевод-статьи-.html)
- [Алан Кэй, создатель ООП, про разработку, Лисп и ООП](https://habr.com/company/hexlet/blog/303754/)
- [Simula — 50 лет ООП](https://habr.com/post/345944/)

![oop](https://user-images.githubusercontent.com/29703461/39483340-b3a50496-4d7a-11e8-8e02-42a8d63de02d.jpg)

## ![video](https://user-images.githubusercontent.com/29703461/81982928-d556fb00-9632-11ea-9794-ea198832d674.png) 2. <a name="2">[Что такое класс](https://drive.google.com/file/d/1AjEL8wuTK6BbiMWB2hhi_Cx6_m7NMrD1/view?usp=sharing)</a>

>Класс — это ссылочный тип данных, являющийся прототипом (blueprint, шаблоном) объекта, описывающий его характеристики и реализующий его поведение

**Материалы:**
- [Класс](https://ru.wikipedia.org/wiki/Класс_(программирование)) (wiki)
- [Классы в Java](https://vertex-academy.com/tutorials/ru/klassy-v-java)
- [Classes](https://docs.oracle.com/javase/tutorial/java/javaOO/classes.html)
- [What Is a Class?](https://docs.oracle.com/javase/tutorial/java/concepts/class.html)
- [Тип данных String(строка) в Java](https://habr.com/post/260767)
![class](https://user-images.githubusercontent.com/29703461/39529699-f6e7e736-4e2f-11e8-8c80-8686cfd56a2e.png)

**Домашнее задание:**
- Создайте класс **Person** (без метода main)
- Напишите в нем поля (атрибуты), описывающие характеристики человека: пол, имя, рост, вес, возраст
- Проинициализируйте их какими-то значениями
- Создайте в классе методы, описывающие поведение (что он может делать) человека: идти, сидеть, бежать, говорить, учить Java
- Покажите Д/З наставнику

## ![video](https://user-images.githubusercontent.com/29703461/81982928-d556fb00-9632-11ea-9794-ea198832d674.png) 3. <a name="3">[Что такое объект](https://drive.google.com/file/d/1hJCGeVRy-4mTTkViK219JzfLKbwLze66/view?usp=sharing)</a>

>Объект — это экземпляр какого-либо класса, обладающий характеристиками в виде полей (fields) и поведением (функционалом) в виде методов (methods)

**Материалы:**
- [Объект](https://ru.wikipedia.org/wiki/Объект_(программирование)) (wiki)
- [What Is an Object?](https://docs.oracle.com/javase/tutorial/java/concepts/object.html)
- [Objects](https://docs.oracle.com/javase/tutorial/java/javaOO/objects.html)

![object](https://user-images.githubusercontent.com/29703461/39529416-4e58a1e6-4e2f-11e8-9a37-029871ea096a.png)

**Домашнее задание:**
- Создайте класс **Wolf**
   - напишите в нем поля: пол, кличка, вес, возраст, окрас
   - напишите в нем методы: идти, сидеть, бежать, выть, охотиться
- Создайте класс **WolfTest** с методом **main**
  - создайте объект типа **Wolf**
  - присвойте в нем полям экземпляра класса **Wolf** какие-то значения
  - считайте эти значения из полей и отобразите в консоли
  - вызовите методы объекта
- Покажите Д/З наставнику

## ![video](https://user-images.githubusercontent.com/29703461/81982928-d556fb00-9632-11ea-9794-ea198832d674.png) 4. <a name="4">[Инкапсуляция: геттеры/сеттеры](https://drive.google.com/file/d/1GWI8rJS6Xwbhz512R4ohdN3b0UKYnnm1/view?usp=sharing)</a>

**Материалы:**
- [Инкапсуляция](https://ru.wikipedia.org/wiki/Инкапсуляция_(программирование)) (wiki)
- [Что такое инкапсуляция](https://www.youtube.com/watch?v=nyFQvgrkoXY) (youtube)
- [Описание инкапсуляции](https://github.com/ichimax/Java-Interview-Questions/blob/master/Questions/1.%20OOP.md#Что-такое-инкапсуляция)
- [Инкапсуляция в Java](https://vertex-academy.com/tutorials/ru/inkapsulyaciya-java/)
- [Инкапсуляция поля](https://refactoring.guru/ru/encapsulate-field)
- [Геттер](https://ru.wikipedia.org/wiki/Геттер_(программирование)), [Сеттер](https://ru.wikipedia.org/wiki/Setter) (wiki)
- [Геттеры и Сеттеры](https://vertex-academy.com/tutorials/ru/gettery-i-settery/)
- [Для чего нужны геттеры и сеттеры](https://javatalks.ru/topics/38059)

## 5. <a name="5"> Ответы на вопросы</a>
> в чем разница между `Классом` и `Объектом`? Или это одно и тоже?

Класс и Объект — это разные понятия. Класс — это «чертеж» на основе которого создаются Объекты. Благодаря этому «чертежу» JVM знает, какой объект ей надо создать

**Домашнее задание:**
- Модифицируйте класс **Wolf**
   - у всех полей класса напишите модификатор доступа `private`
   - у всех методов класса напишите модификатор доступа `public`
   - для доступа к полям создайте геттеры и сеттеры
   - в сеттере поля `age` реализуйте проверку: если возраст волка > 8 лет, то выведите сообщение "Некорректный возраст"
- Модифицируйте класс **WolfTest**  
  - с помощью сеттеров присвойте полям экземпляра класса **Wolf** какие-то значения
  - считайте эти значения из полей с помощью геттеров и отобразите в консоли
- Покажите Д/З наставнику

## 6. <a name="6">Домашнее задание</a>

> Перед отправкой домашнего задания на проверку обращайте внимание на [`Советы для тех, кто выполняет домашнее задание`](https://github.com/ichimax/startjava/blob/master/lesson%202.md#7-советы-для-тех-кто-выполняет-домашнее-задание), которые содержат ряд полезных подсказок и разъяснений
- Прочитайте вторую, третью (со стр 84) и четвертую главы книги [Изучаем Java](https://www.ozon.ru/context/detail/id/7821666/)
- Начните потихоньку читать — [Объектно-ориентированное мышление. Мэтт Вайсфельд](https://www.ozon.ru/context/detail/id/26036833/)
- Модифицируйте программу `Калькулятор`:
  - реализуйте дополнительный класс `CalculatorTest`, перенеся в него метод main
  - класс `Calculator` будет отвечать за проверку знака и мат. вычисления
  - для проверки знака математической операции воспользуйтесь оператором [`switch`](https://youtu.be/QJHcGWbzk3U)
  - для ввода мат. выражения используйте клавиатуру (класс [`Scanner`](https://vertex-academy.com/tutorials/ru/rabota-so-skannerom-v-java/))
  -  формат ввода математического выражения:  
    `Введите первое число: 2`   
    `Введите знак математической операции: ^`  
    `Введите второе число: 10`
- Модифицируйте класс `Jaeger`, сделав его универсальным (без инициализации полей в самом классе, как мы это делали в уроке). Это позволит на его основе создавать любого робота:
  - информацию о роботах можно найти [здесь](http://pacificrim.wikia.com/wiki/Category:Jaegers)
  - выберите два или более разных роботов. Найдите между ними что-то общее (поля, методы). Реализуйте это в коде (не усложняйте реализацию. Делайте все максимально просто)
  - создайте 2 экземпляра класса `Jaeger` в классе `JaegerTest`и поэкспериментируйте с ними (проинициализируйте поля, вызывайте методы, перезаписывайте и выводите значения полей)
  - для инициализации полей объектов при их создании используйте в начале сеттеры (покажите решение ментору), а потом перепишите, используя [конструктор](https://youtu.be/f88zS-etDWs)
- Модифицируйте программу `Угадай число`:
  - реализуйте класс `GuessNumber`, `Player` и `GuessNumberTest`
  - создайте двух игроков, которые по очереди будут пытаться угадать число (вводя его с клавиатуры), загаданное компьютером
  - введите с клавиатуры в начале игры имена каждого игрока
  - поля объектов, создаваемых в программе, инициализируйте с помощью конструкторов (Игроки, Игра - это объекты)
  - для генерации компьютером псевдослучайного числа в диапазоне от 0 до 100 используйте класс [`Random`](https://www.journaldev.com/17111/java-random) или [`Math.random()`](https://vertex-academy.com/tutorials/ru/generaciya-sluchajnyx-chisel-v-java)
  - одержать победу может только один игрок
  
 ## 7. <a name="7">Советы для тех, кто выполняет домашнее задание</a> 
 1. Назначение классов в `Калькулятор`:
    - `Calculator` — отвечает за вычисления и проверку мат. знака
    - `CalculatorTest` — отвечает за создание объектов, их инициализацию, запуск вычислений, ввод мат. выражения. Содержит метод main 
 1. Назначение классов в игре `Угадай число`:
    - `GuessNumber` — отвечает за весь игровой процесс
    - `Player` — описывает игроков (один экземпляр класса соответствует одному игроку)
    - `GuessNumberTest` — отвечает за создание объектов, их инициализации, запуска игры. Содержит метод main
 1. Для завершения или продолжения работы программ `Калькулятор` и `Угадай число` выводите сообщение: `"Хотите продолжить? [да/нет]:"`. Если пользователь ввел ни "да" ни "нет", а что-то другое — снова выведите сообщение `"Хотите продолжить? [да/нет]:". (Реализуйте эту логику в Test-классах)
 1. Как, используя класс Scanner, получить тип данных char? Например, [так](https://stackoverflow.com/questions/23098790/how-can-i-enter-char-using-scanner-in-java):
 `char sign = scan.next().charAt(0);`
 1. Если вам кажется, что Scanner работает не так, как вы ожидаете, то ознакомьтесь с [этой статьей](https://ru.stackoverflow.com/questions/526818/scanner-%D0%BD%D0%B5-%D1%81%D1%87%D0%B8%D1%82%D1%8B%D0%B2%D0%B0%D0%B5%D1%82-%D1%81%D1%82%D1%80%D0%BE%D0%BA%D1%83-%D0%BF%D0%BE%D1%81%D0%BB%D0%B5-nextint)
 1. Не забывайте указывать для полей и методов модификаторы доступа
 1. Класс `Player` должен иметь следующие поля и методы:
    - `String name` — имя игрока (**одного!**)
    - `int number` — введенное пользователем число
    - геттеры/сеттеры (по необходимости)    
 1. Так должна выглядеть структура ваших файлов и папок
 
 ![tree](https://user-images.githubusercontent.com/29703461/40511256-c839671e-5fa7-11e8-820d-6e5534c4ac7f.png)
