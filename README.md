# HomeWork #1 12.02
Створити веб-проєкт, добитись його запуску
Реалізувати сервлет для нової сторінки "privacy", забезпечити її відображення через шаблон (layout)
Додати посилання на неї до головної сторінки.



# HomeWork #2 14.02
Забезпечити випробування інжектора сервісів:


Вивести у складі сторінки "іос"
- випадкового коду (з сервіса кодів)
- його хешу (з сервіса хешування).
Дані мають змінюватись з оновленням сторінки.
<a herf="https://github.com/AntonDegt/JavaWeb/tree/master/src/main/java/step/learning/services">**СЕРВІСИ**</a>



# HomeWork #3 16.02
Реалізувати повну валідацію 
імені користувача, що вводиться у формі:
- не порожнє
- довше, ніж 1 символ
* відповідає шаблону "перша літера велика, решта маленькі"
Виводити різні повідомлення при різних відхиленнях валідації
<a href="https://github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/servlets/SignUpServlet.java#L69">**ФАЙЛ**</a>



# HomeWork #4 19.02
Завантаження файла-аватарки:
забезпечити перевірку переданого файлу на допустимість
типу (розширення) за переліком (створити самостійно).
За навності помилок вивести їх в UI (на формі реєстрації)
<a href="https://github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/servlets/SignUpServlet.java#L92">**ФАЙЛ**</a>




# Home Work #5 21.02
Реалізувати реєстрацію користувачів із занесенням до БД. 
Зареєструвати декілька тестових користувачів (запам'ятати паролі).
Налаштувати реєстрацію без аватарок, кільком користувачам не зазначити їх.
Додати скріншот витягу з БД.



# Home Work #6 23.02
Провести налаштування та випробування логеру:
- внести до SQL запитів помилки, переконатись у появі
- повідомлень про винятки, а також самого тексту запиту
<a href="github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/ioc/LoggerModule.java">**ФАЙЛ**</a>



# Home Work #7 26.02
Реалізувати поглиблену валідацію одержаних даних автентифікації
Використати шаблони перевірки (регулярні шаблони)
<a href="github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/servlets/SignUpServlet.java">**SignUpServlet.java**</a>



# Home Work #9 28.02
Вивести аватарку користувача після його входу до системи (авторизації)
За відсутності аватарки в авторизованого користувача - вивести no-photo.png
<a href="https://github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/webapp/WEB-INF/profile.jsp#L12">**profile.jsp#L12**</a>



# Home Work #10 01.03
Створити фільтр, який буде задавати кодування символів для request та response усіх запитів
(див AuthServlet::doGet)
Поставити фільтр на саме перше місце (кодування не можна змінювати, якщо вже відбулись читання чи запис до request / response)
<a href="https://github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/servlets/AuthServlet.java#L28">**AuthServlet.java#L28**</a>



