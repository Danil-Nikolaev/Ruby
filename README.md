# Дисциплина языки-интернет программирования
## Задание
Все консольные приложения Ruby следует реализовывать в виде трех
отдельных файлов:
1. основная программа;
2. программа для взаимодействия с пользователем через консоль;
3. программа для автоматического тестирования на основе MiniTest::Unit или RSpec. Везде, где это возможно, данные для проверки должны формироваться автоматически по правилам, указанным в задании.
При реализации программ везде, где это возможно, следует избегать использования циклов for, do, while. Вместо них используйте методы из примеси Enumerable.
Все тексты программ должны быть проверены на соответствие стилю программирования Ruby при помощи rubocop .ruи reek.

### ЛР1

1. Выполните разметку HTML-страницы с использованием элементов семантической разметки текста (см. таблицу 6). Напишите не менее 10 строк произвольного текста. Выделите в каждой строке несколько слов как более важные, значительно важные, добавьте математические формулы и пр. Также, с использованием семантической разметки, добавьте к тексту произвольные строки кода на любом языке программирования. Подготовьте второй вариант разметки, отличающийся выделенными словами. Замените фрагменты, которые ранее отображались курсивом на фрагменты, отображаемые жирным шрифтом.

2. Сформируйте HTML-страницу с фрагментом расписания занятий (используйте элемент table). Выберите фрагмент расписания таким образом, чтобы хотя бы в одном месте возникала необходимость объединения ячеек таблицы.

3. Подготовьте разметку формы регистрации на произвольном сайте. Для расположения элементов используйте табличную верстку.

4. Используя валидаторы HTML (предустановленный в браузере или https://validator.w3.org/), проверьте полученные HTML-страницы на наличие ошибок. Составьте таблицу выявленных ошибок, в которую внесите все ошибки валидации и их фактические проявления в браузере. Устраните все найденные ошибки.

### ЛР2

1. Часть 1

	1.1. Подготовьте разметку произвольного текста, содержащего не менее 10 строк (могут быть использованы материалы из лабораторной работы № 1) с 		использованием таблицы стилей. Продемонстрируйте выделение отдельных слов с помощью стилей, цвета и шрифта.
	
	1.2. С использованием элементов div подготовьте разметку таблицы, например, содержащей фрагмент расписания.
	
2. Часть 2

	2.1. Возьмите шаблон страницы Bootstrap (см. Приложение Б). Измените цвет фона навигационной панели и подвала сайта на свое усмотрение.
	
	2.2 Вставьте:
	
	- на место текста “Вставьте сюда форму” форму из лабораторной работы 1;
	- на место текста “Вставьте сюда таблицу” произвольную таблицу (на основе элементов table/tr/td);
	- на место текста “Вставьте сюда текст” блок разметки текста (из пункта 1).
Добавьте классы Bootstrap в элементы формы, и заголовки таблицы.

3. Проверьте полученные HTML-страницы на наличие ошибок. Составьте таблицу выявленных ошибок, в которую внесите все ошибки валидации и их фактические проявления в браузере. Устраните все найденные ошибки.

### ЛР 3
Задание 
Написать Javascript-код для вывода дерева элементов страницы, с которой этот код запущен. Отступы для отображения формировать как символ   В процессе выполнения работы реализовать следующие пункты: 
1. Сформировать страницу с произвольным кодом разметки, но обеспечить уровень вложенности внутри элемента не менее 3. 
2. добавить внутри элемента секцию , предназначенную для вывода результата обхода дерева элементов страницы. 
3. Выбрать способ активации рекурсивной программы обхода дерева элементов, реализовать и подключить эту программу. 
4. При проходе по узлам разметки обеспечить отладочный вывод в консоль. Привести в отчете содержимое консоли. 
5. Реализовать вывод на странице.

### ЛР 4

Задание 
Разработать страницу для оформления заказа товаров. 
	1. Реализовать форму для ввода наименования и стоимости. При нажатии на кнопку «Добавить», добавить введенные значения в таблицу. 
	2. Сделать кнопку расчёта стоимости заказа. 
	3. Поставить обработчик на изменение фона ячеек таблицы со стоимостью в тот момент, когда над ними находится указатель мыши. 
	4. Подготовить страницу, содержащую таблицу товаров и их стоимости. На базе этой страницы обеспечить возможность выбора строк и добавления их в таблицу формирования заказа

### ЛР 5
### Часть 1

Вычислить: y = sin(x) + x2 − 2ex /(x3 − 5)

### Часть 2

Данные о температуре воздуха хранятся в виде двух массивов, где по-
парно представлены дата и температура. Определить, сколько раз тем-
пература опускалась ниже –10 градусов за количество дней, введённых
с клавиатуры. Распечатать в виде таблицы эти даты и температуры.

### Часть 3

Дана последовательность строк. Каждая строка состоит из слов, раз-
деленных пробелами, в конце — точка. Слова в строке образуют пары:
каждое первое слово — заменяемое, каждое второе — замещающее. Напи-
сать программу, обеспечивающую ввод строк и их корректировку. Кор-
ректировка заключается в замене всех заменяемых слов замещающими.
Вывести на печать исходную и скорректированную последовательности
строк.

Автоматический тест программы обязательно должен генерировать
случайные строки в соответствии с правилами, перечисленными в зада-
нии.

### ЛР 6

### Часть 1

Решить задачу, организовав итерационный цикл с точностью ξ = 10−4 , 10−5 .
Вычислить значение определенного интеграла методом прямоугольников: x sin x2 dx. 
Точное значение: (1 − cos 1). Определить, как изменяется число итераций при изменении точности.

### Часть 2

Решить предыдущее задание с помощью Enumerable или Enumerator.

### ЛР 7

### Часть 1

Сформировать программным путем символьный файл F, содержащий
слова. Считая, что количество символов в слове не превосходит двадцати
определить, сколько в файле F имеется слов, состоящих из двух симво-
лов.
Автоматический тест программы обязательно должен проверять ра-
боту с файлами.

### Часть 2

Разработать и реализовать иерархию классов для описанных объектов предметной области, используя механизмы наследования. Проверить ее на тестовом примере, с демонстрацией всех возможностей разработанных классов на конкретных данных.

Объект — Треугольник, заданный точками на плоскости. Объект умеет выводить на экран значение своих полей и отвечать на запрос об этих значениях и вычислять площадь фигуры.

Объект — Треугольная призма. Объект умеет выводить на экран содержимое своих полей, возвращать по запросу их значения и площадь развертки.
В тестирующей программе обеспечить автоматическую проверку того, что созданные объекты действительно соответствют заданной иерархии классов.

### ЛР 8. Ruby on Rails
Разработать веб-приложение, имеющее HTML-страницу с формой ввода данных и HTML-страницу для представления результатов. Результат расчёта должен быть представлен в форме таблицы, оформленной с помощью элемента table или отдельными ячейками div и имеющей не менее двух колонок. Если по условию задания результат может быть представлен только в виде одной строки таблицы, необходимо реализовать вывод промежуточных результатов расчёта в качестве дополнительных строк. В этом случае первой колонкой таблицы будет порядковый номер итерации.

Под вводом с клавиатуры в тексте заданий следует понимать ввод в поле ввода данных формы на HTML-странице.

Текст задания:

Известно, что произведение двух целых чисел, деленное на их наибольший общий делитель, дает наименьшее общее кратное.

Написать программу, определяющую наибольший общий делитель двух целых чисел n и m (n, m вводятся с клавиатуры), используя известный алгоритм Евклида и наименьшее общее кратное этих же чисел,опираясь на утверждение, сделанное в начале. 

Вывести на печать все найденные числа и результаты промежуточных итераций. При программировании использовать функции.

### ЛР 9

1.При помощи Javascript модифицировать код ЛР 8 таким образом, чтобы для отображения результатов вычисления браузер не выполнял полную перезагрузку страницы.

2.Сформировать тесты для проверки работы программы при помощи Katalon Recorder / Selenium Webdriver.

### ЛР 10

Модифицировать код ЛР 8 таким образом, чтобы по запросу с указанными параметрами выдавался результат в формате XML (средствами стандартной сериализации ActiveSupport).

• Проверить формирование XML и сохранить в файл для отладки XSLT и второго приложения.

• Написать функциональный тест, проверяющий формат выдаваемых данных при запросе RSS.
    
Разработать XSLT-программу преобразования полученной XML в HTML.
Добавить в проверяемый XML-файл строку привязки к преобразованию <?xml-stylesheet type="text/xsl" href="some_transformer.xslt"?>. Проверить корректность отображения браузером результата преобразования.
Проверить на автономной Ruby-программе корректность преобразования, используя следующий фрагмент кода:
```
require 'nokogiri'
doc = Nokogiri::XML(File.read('some_file.xml'))
xslt = Nokogiri::XSLT(File.read('some_transformer.xslt'))
puts xslt.transform(doc)
```
Разработать второе приложение, являющееся посредником между клиентом и первым приложением, задачей которого является преобразование XML в HTML или передача в неизменном виде браузеру для отображения браузером. Приложение должно запускаться с указанием номера порта TCP, отличным от номера порта первого приложения (например rails server -p 3001)!

• Подготовить каркас приложения, а также форму формирования запроса, форму отображения результата и соответствующие действия контролера.

• Добавить в контроллер преобразование XML в HTML с помощью ранее разработанного XSLT-файла.

• Подключить запрос XML с первого приложения и проверить работу приложений в связке.

• Написать функциональный тест, проверяющий что при различных входных данных результат генерируемой страницы различен.

• Доработать код контроллера и представлений данного приложения для выдачи браузеру XML-потока в неизменном виде (организовать возможность выбора формата выдачи для пользователя).

• Проверить, что браузер получает XML первого приложения в неизменном виде.

• Доработать код контроллера приложения таким образом, чтобы XML-поток первого приложения получал дополнительную строку, указывающую xsl. Модифицировать форму запроса параметров таким образом, чтобы браузер получал в ответ XML. При этом разместить XSLT-файл в директории public.

• Проверить, что браузер производит преобразование XML->HTML в соответствии с xlt.

• Реализовать функциональные тесты второго приложения. Проверить результаты, формируемые приложением, на соответствие выбранному формату выдачи.
Итоговая форма ввода параметра должна содержать кнопки или селектор, позволяющие проверить два варианта преобразования:

- Серверное xml+xslt->html
- Клиентское xml+xslt->html

### ЛР11

Модифицировать код ЛР 8 таким образом, чтобы запросы, которые были ранее выполнены, сохранялись в БД и при следующем запросе не требовали повтора вычислений.

• Сформировать модель в соответствии с потребностями хранения данных. Входные параметры являются ключами, по которым извлекается результат.

• Выполнить создание БД и миграцию соответствующими запросами rake.

• Написать тест на добавление и поиск данных с помощью модели. Проверить выполнение теста.

• Модифицировать код приложения таким образом, чтобы результат вычислений преобразовывался в строковый или бинарный формат (на выбор: json, xml, и пр.). Проверить через отладочную печать в консоль, что преобразование выполняется корректно.

• Вставить код для сохранения данных в БД и запрос на поиск предыдущего результата вычислений.

• Добавить действие в контроллер, позволяющее определить, что хранится в БД через сериализацию в XML.

• Проверить, что при выполнении запроса, данные добавляются в БД.

• При помощи консоли сообщений Puma/Webrick определить, производится ли поиск результата предыдущего запроса в БД и не повторяются ли одни и те же вычисления.
    
• Модифицировать модель таким образом, чтобы добавление записей с одинаковыми параметрами было невозможно.

• Реализовать тест модели, проверяющий невозможность повторного добавления одних и тех же результатов вычислений.

• Реализовать функциональный тест, проверяющий, что результаты вычислений различны при различных входных параметрах.

• Проверить маршруты приложения с помощью rake routes и убрать лишние. Обеспечить доступ при обращении по адресу /.

### ЛР 12

Модифицировать код приложения ЛР 8 таким образом, чтобы вычисление было невозможно без регистрации пользователя и аутентификации при помощи логина/пароля.

• Сгенерировать при помощи генератора scaffold ресурс для регистрации пользователей.

• Создать БД и выполнить миграцию соответствующим запросом rake.

• Проверить возможность добавления, редактирования информации и получения списка пользователей.

• Удалить отображение поля пароля при просмотре списка пользователей.

• Добавить контроллер сессий.
    
• Реализовать форму для ввода логина/пароля при обращении по адресу /. Добавить ссылку на регистрацию нового пользователя. При успешном вводе логина/пароля должно осуществляться перенаправление на страницу ввода параметров для вычисления.

• Реализовать при помощи контроллера сессий во всех действиях контроллера проверку о того, прошел ли пользователь аутентификацию или нет (с выдачей соответствующей отладочной информации).

• Вставить фильтры для запроса аутентификации.

• Подготовить интеграционный тест, позволяющий проверить регистрацию нового пользователя, вход под его именем и выполнение вычислений.

• Подготовить интеграционный тест для проверки невозможности выполнения вычислений без ввода логина/пароля.

• Проверить маршруты приложения с помощью rake routes и убрать лишние. Обеспечить доступ при обращении по адресу /.

## P.S.
Каждая лабораторная работа (и его задание) размещена на отдельной ветке.
