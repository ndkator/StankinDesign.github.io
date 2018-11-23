## Королецкий П.В. ИДБ-15-12.
![](https://78.media.tumblr.com/0571b840545e623ef455448f024be550/tumblr_pf24ziPkjR1rpcmy2o1_400.jpg)

![](https://github.com/ndkator/ndkator.github.io/blob/master/1/MOD1.svg)
## Лабораторная работа №1

**Модель-шаблон (IDEF0):**
* Ссылка на модель (RSF): [клац](https://github.com/ndkator/ndkator.github.io/blob/master/1/Model.rsf)
* Ссылка на модель (PNG): [клац](https://github.com/ndkator/ndkator.github.io/blob/master/1/Model.png)
* Ссылка на модель (HTML): [клац](https://ndkator.github.io/1/Home1.html)

**Индивидуальная работа (IDEF0):**
* Ссылка на модель (RSF): [клац](https://github.com/ndkator/ndkator.github.io/blob/master/1/Auth.rsf)
* Ссылка на модель (HTML): [клац](https://ndkator.github.io/1/HomeAuth.html)
* Модель (PNG): ![](https://github.com/ndkator/ndkator.github.io/blob/master/1/Auth.png)

**Индивидуальная работа (UML, диаграмма классов):**
* Ссылка на модель (TXT): [клац](https://github.com/ndkator/ndkator.github.io/blob/master/1/first.txt)
* Модель (PNG): 

![](https://github.com/ndkator/ndkator.github.io/blob/master/1/first.png)

**Индивидуальная работа (UML, диаграмма прецедентов):**
* Ссылка на модель (TXT): [клац](https://github.com/ndkator/ndkator.github.io/blob/master/1/second.txt)
* Модель (PNG): ![](https://github.com/ndkator/ndkator.github.io/blob/master/1/second.png)

## Лабораторная работа №2
**Индивидуальная работа (IDEF0, A0, A1-A3):**
* Ссылка на модель (RSF): [клац](https://github.com/ndkator/ndkator.github.io/blob/master/2/my.rsf)
* Модель (PNG): ![](https://github.com/ndkator/ndkator.github.io/blob/master/2/A0.png)
* Модель (PNG): ![](https://github.com/ndkator/ndkator.github.io/blob/master/2/A1-A3.png)

## Лабораторная работа №3
**Индивидуальная работа (A1-DFD, A2-DFD):**
* Ссылка на модель (RSF): [клац](https://github.com/ndkator/ndkator.github.io/blob/master/3/LR3.rsf)
* Модель (PNG): ![](https://github.com/ndkator/ndkator.github.io/blob/master/3/03_A1_.png)
* Модель (PNG): ![](https://github.com/ndkator/ndkator.github.io/blob/master/3/04_A2.png)

![](https://github.com/ndkator/ndkator.github.io/blob/master/1/MOD2.svg)
## Лабораторная работа №4. Подготовка диаграмм IDEF0 курсового проекта
**1. Определение требований к модели:**
* Моделируемый процесс: обеспечение безопасности БЛВС
* Точка зрения: проектировщик системы безопасности БЛВС
* Цели моделирования: "Визуализация процесса создания проекта по обеспечению безопасности БЛВС"
* Тема курсового проекта: "Создание проекта по обеспечению безопасности БЛВС"

**2. Разработка диаграмм в RAMUS:**
* [Ссылка на модель (RSF)](https://github.com/ndkator/ndkator.github.io/blob/master/4/Course.rsf)
* Контекстная диаграмма: ![](https://github.com/ndkator/ndkator.github.io/blob/master/4/01_A0.png)
* A0: ![](https://github.com/ndkator/ndkator.github.io/blob/master/4/02_A0.png)
* A1: ![](https://github.com/ndkator/ndkator.github.io/blob/master/4/03_A1.png)
* A2: ![](https://github.com/ndkator/ndkator.github.io/blob/master/4/04_A2.png)
* A3: ![](https://github.com/ndkator/ndkator.github.io/blob/master/4/05_A3.png)
* A4: ![](https://github.com/ndkator/ndkator.github.io/blob/master/4/06_A4.png)
* A5: ![](https://github.com/ndkator/ndkator.github.io/blob/master/4/07_A5.png)

## Лабораторная 5. Подготовка диаграмм DFD курсового проекта
**1. Определение основных средств автоматизации:**
* Определение конфигурации технических средств: точки доступа (хранят лог-файлы), ноутбук (рабочая станция, ассоциирующаяся с точкой доступа)
* Определение конфигурации программных средств (одноуровневые, многоуровневые, 
встроенные, распределенные): ???
* Определение допустимых видов хранилищ и их размещения: ???

**2. Разработка диаграмм в RAMUS:**
* [Ссылка на модель (RSF)](https://github.com/ndkator/ndkator.github.io/blob/master/5/Course.rsf)
* Произведена декомпозиция блока A43 в DFD
* Типы каждого блока в DFD: 1,3 - экранная форма; 2,4- печатная форма; 5 - модуль  
обработки
* Типы хранилищ в DFD: `БД: Hacking tools` и `БД:Аудит` — это таблицы БД, в которых содержатся сведения о известных технологиях, используемых при пентесте, а также результаты аудита соответственно. `Лог-файлы точек доступа` — это файлы, содержащие структурированную по времени информацию о результатах подключений клиентов к ТД и много другой полезной информации
* A43: ![](https://github.com/ndkator/ndkator.github.io/blob/master/5/07_A43.png)
P.S. В процессе создание декомпозиции DFD незначительно изменилась структура IDEF0, а именно: 
- добавлены ограничения `Семейство стандартов IEEE 802.11` и `Требования к оформлению`
- добавлен исполнитель `Эксперт в области безопасности сетей`

Обновленные IDEF0 можно лицезреть здесь: [в цвете](https://github.com/ndkator/ndkator.github.io/blob/master/5/) или [ч/б вариант](https://github.com/ndkator/ndkator.github.io/blob/master/5/models(mono))

## Лабораторная 6. Подготовка диаграмм UML курсового проекта
**Завершение идентификации всех потоков
* Построение ERD (диаграммы классов без атрибутов) для всех потоков
**Завершение идентификации всех ролей
* Построение ERD (диаграммы классов без атрибутов) для всех ролей
* UML: ![](https://github.com/ndkator/ndkator.github.io/blob/master/6/Роли.png)
**Завершение идентификации всех модулей
* Построение ERD (диаграммы классов без атрибутов) для всех модулей
* UML: ![](https://github.com/ndkator/ndkator.github.io/blob/master/6/модули.png)
