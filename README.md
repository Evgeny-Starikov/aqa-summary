 # План тестирования возможности записаться на обучение профессии «Инженер по тестированию»
 
 ## Перечни автоматизируемых сценариев

 ### Сценарии навигации к странице профессии

#### Навигация через раздел "Направления обучения"
A)
Открыть страницу сайта Нетологии.
Пролистать страницу до блока "Направления обучения"
Кликнуть на кнопку "Полный каталог"
Пролистать страницу до формы «Инженер по тестированию».
Кликнуть на курс «Инженер по тестированию».
Кликнуть кнопку "Записаться".
Заполнить форму "Запишитесь на курс".

*Ожидаемый результат:* открыта форма для ввода личных данных и записи на курс.

B)
Открыть страницу сайта Нетологии.
Пролистать страницу до блока "Направления обучения"
Кликнуть по кнопке "Программирование" (при ее отображении на странице раздела).
Кликнуть курс "Инженер по тестированию".
Кликнуть кнопку "Записаться".
Заполнить форму "Запишитесь на курс".

*Ожидаемый результат:* открыта форма для ввода личных данных и записи на курс.


#### Навигация через меню каталога курсов

A)
Открыть страницу сайта Нетологии.
Кликнуть на кнопку меню «Каталог курсов».
Кликнуть на блок курсов «Программирование».
Пролистать страницу до формы «Инженер по тестированию».
Кликнуть на курс «Инженер по тестированию».
Кликнуть кнопку "Записаться".
Заполнить форму "Запишитесь на курс".

*Ожидаемый результат:* открыта форма для ввода личных данных и записи на курс.

B)
Открыть страницу сайта Нетологии.
Кликнуть на кнопку меню «Каталог курсов».
В поисковике ввести "тестирование".
Выбрать курс Инженер по тестированию
Кликнуть кнопку "Записаться".
Заполнить форму "Запишитесь на курс".

*Ожидаемый результат:* открыта форма для ввода личных данных и записи на курс.


### Сценарии заполнения и отправки формы "Запишитесь на курс"

1. **Успешная запись с валидными данными**

Открыть страницу записи на курс «Инженер по тестированию».
Кликнуть на кнопку «Записаться».
Заполнить поля валидными данными:
Имя (имя на кириллице, например, Евгений);
Номер телефона в формате +x yyy zzzzzzz, гед +x - префикс страны (в некоторых странах вместо знака + в префиксе может быть знак -), yyy - код оператора или населенного пункта, zzzzzzz (номер мобильного либо стационарного телефона), например, +79537434515.
*__Ожидаемый результат:__ Отображается сообщение об успешной записи и о том, что в ближайшее время с вами свяжутся для оформления на курс.* 

2. **Отправка формы с пустыми обязательными полями**
   
Открыть страницу записи на курс «Инженер по тестированию».
Оставить обязательные поля пустыми.
Кликнуть на кнопку "Записаться".
*__Ожидаемый результат:__ Отображается сообщение об ошибке: "Поле должно быть заполнено"*

3. **Ввод невалидного номера телефона, состоящего из 1 цифры**

Открыть страницу записи на курс «Инженер по тестированию».
Заполнить поле имя валидным значением.
Ввести невалидный номер телефона, состоящий из 1 цифры (например, 0).
Кликнуть на кнопку "Записаться".
*__Ожидаемый результат:__ Отображается сообщение об ошибке: "Проверьте правильность ввода номера телефона"*

4. **Ввод невалидного номера телефона, состоящего из 2 цифр**

Открыть страницу записи на курс «Инженер по тестированию».
Заполнить поле имя валидным значением.
Ввести невалидный номер телефона, состоящий из 2 цифр (например, 88).
Кликнуть на кнопку "Записаться".
*__Ожидаемый результат:__ Отображается сообщение об ошибке: "Проверьте правильность ввода номера телефона"*

5. **Ввод невалидного номера телефона, состоящего из 10 цифр**

Открыть страницу записи на курс «Инженер по тестированию».
Заполнить поле имя валидным значением.
Ввести невалидный номер телефона, состоящий из 10 цифр (например, 7900000000).
Кликнуть на кнопку "Записаться".
*__Ожидаемый результат:__ Отображается сообщение об ошибке: "Проверьте правильность ввода номера телефона"*

6. **Ввод невалидного номера телефона, состоящего из 11 цифр**

Открыть страницу записи на курс «Инженер по тестированию».
Заполнить поле имя отправки формы с пустым полем "Имя"
*__Ожидаемый результат:__ Поле не принимает значение. Ввод лишних символов в поле невозможен*

7. **Отправка формы с пустым полем "Имя"**

Открыть страницу записи на курс «Инженер по тестированию».
Заполнить поле "Телефон" валидным значением.
Кликнуть на кнопку "Записаться".
*__Ожидаемый результат:__ Отображается сообщение об ошибке: "Поле должно быть заполнено"*

8. **Отправка формы с пустым полем "Телефон"**

Открыть страницу записи на курс «Инженер по тестированию».
Заполнить поле "Имя" валидным значением.
Кликнуть на кнопку "Записаться".
*__Ожидаемый результат:__ Отображается сообщение об ошибке: "Поле должно быть заполнено"*

9. **Отправка формы с именем на языке (раскладке клавиатуры), отличном от русского**

Открыть страницу записи на курс «Инженер по тестированию».
Заполнить поле "Имя" значением на латинице (иероглифами, арабским шрифтом и т.п.). Например, Evgeny, エフゲニー, 叶夫根尼, يفغيني (латинская, японская, китайская, арабская транслитерация)
Заполнить поле "Телефон" валидным значением.
Кликнуть на кнопку "Записаться".
*__Ожидаемый результат:__ Отображается сообщение об ошибке: "Проверьте правильность ввода имени. Допускаются пробелы, тире, буквы кирилицы"*

10. **Отправка формы с именем, содержащим спецсимовлы**

Открыть страницу записи на курс «Инженер по тестированию».
Заполнить поле "Имя" значением со спецсимоволами, например, Евгений@, Евгений&.
Заполнить поле "Телефон" валидным значением.
Кликнуть на кнопку "Записаться".
*__Ожидаемый результат:__ Отображается сообщение об ошибке: "Проверьте правильность ввода имени. Допускаются пробелы, тире, буквы кирилицы"*


## Перечень используемых инструментов с обоснованием выбора

1. **Selenide**: надежность в работе с динамическими элементами страницы. Хороший инструмент для тестирования веб-приложений.
Стабильность и надежность в работе с динамическими элементами страницы.
2. **WebDriver**: совместимый с Selenide инструмент для управления браузерами.
3. **Allure**: инструмент для генерации наглядных и подробных отчетов о тестировании.
4. **Dev Tools:** встроенная фича браузера, позволяет находить селекторы и другие данные.
5. **Postman**: - удобный инструмент для отправки запросов на сервер и анализа ответов.
6. **JUnit**: фреймворк для написания и организации тестов. Поддерживает аннотации, параметризацию и гибкую конфигурацию тестов. Интегрируется с Allure.
7. **GIT**: распределённая система управления версиями для хранения истории версий кода. 
8. **GitHub**: веб-сервис и хостинг для проектов, использующих **Git** в качестве системы контроля версий. 
9. **CI** - (здесь Continuous Integration by GitHub Actions): интеграция отдельных кусочков кода приложения между собой с помощью GitHub Actions. Проверка сборки  и прохождения автотестов. Обнаружение и исправление ошибок на ранних стадиях разработки.
10. **Кофе-машина или коффейный аппрат** с необходимыми расходниками: - для поддержания работоспособности персонала в течение рабочего времени.


## Перечень необходимых разрешений, данных и доступов

1. Доступ к базе данных 
2. Доступ к тестовому серверу сайта. Разрешение применения автотестов.
3. Доступ к тебованиям для их анализа
4. Доступ к тестовым аккаунтам и учетным записям.


## Перечень и описание возможных рисков

1. Проблемы доступа и подключения к интернету или серверу: отсутствие или иные проблемы подключения к интернету может приостановить процесс и привести к увеличению сроков тестирования. Недоступность сервера или базы данных может приостановить  тестирование.
2. Обновления и изменения в структуре сайта - регулярные апы и переверстка могут сломать автотесты.
3. Скорость загрузки элементов сайта - загрузка некоторых элементов значительно позже остальных может повлиять на стабильность тестов и привести к ошибочному заведению бага.
4. Проблемы, связаные с самим тестировщиком: здоровье, семейные, психологические проблемы и т.п.
5. Природные и техногенные ЧС и другие форсмажоры.


## Перечень необходимых специалистов для автоматизации.

Инженер по автоматизированному тестированию
- Создание и поддержка автоматизированных тестов.
- Разработка тестовых сценариев и отчетов.
- Настройка интеграции c GitHub Actions.
- Заведение баг-репортов при нахождении багов и контроль их исправления.


## Интервальная оценка с учётом рисков в часах.

Исследование и анализ сайта и способов перехода к заданной странице, а также требований (если дадут доступ). - 10 ч.
Разработка и написание тестов для перехода к странице профессии различными путями, разработка и  написание тестов для пролистывания страниц и перехода к форме записи, ввола данных в поля и отправки формы - 44 ч.
Настройка Allure - настройка и генерация отчетов - 6 ч.
Настройка CI - настройка workflow на Git Hub - 2 ч.
Применение автотестов - тестирование и отладка сценариев, выявление возможное устранение дефектов - 24 ч. 

**Всего**: 88 часов.
