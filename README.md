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




# HomeWork #5 21.02
Реалізувати реєстрацію користувачів із занесенням до БД. 
Зареєструвати декілька тестових користувачів (запам'ятати паролі).
Налаштувати реєстрацію без аватарок, кільком користувачам не зазначити їх.
Додати скріншот витягу з БД.



# HomeWork #6 23.02
Провести налаштування та випробування логеру:
- внести до SQL запитів помилки, переконатись у появі
- повідомлень про винятки, а також самого тексту запиту
<a href="github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/ioc/LoggerModule.java">**ФАЙЛ**</a>



# HomeWork #7 26.02
Реалізувати поглиблену валідацію одержаних даних автентифікації
Використати шаблони перевірки (регулярні шаблони)
<a href="github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/servlets/SignUpServlet.java">**SignUpServlet.java**</a>



# HomeWork #9 28.02
Вивести аватарку користувача після його входу до системи (авторизації)
За відсутності аватарки в авторизованого користувача - вивести no-photo.png
<a href="https://github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/webapp/WEB-INF/profile.jsp#L12">**profile.jsp#L12**</a>



# HomeWork #10 01.03
Створити фільтр, який буде задавати кодування символів для request та response усіх запитів
(див AuthServlet::doGet)
Поставити фільтр на саме перше місце (кодування не можна змінювати, якщо вже відбулись читання чи запис до request / response)
<a href="https://github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/servlets/AuthServlet.java#L28">**AuthServlet.java#L28**</a>



# HomeWork #11 04.03
Фільтри:
- Додати налаштування для фільтрів, у т.ч. фільтра для зміни кодування, з урахуванням того, що на ресурси вони не повинні спрацьовувати.
<a href="https://github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/filters/EncodingFilter.java">**EncodingFilter.java**</a>



# HomeWork #12 06.03
Поглибити валідацію даних, які надходять для створення новини
- назва: не коротше 10 символів
- анонс: не коротше 10 слів
- дата: відповідає формату yyyy-mm-dd
- контент: не коротше 300 символів
- файл-картинка: має графічний тип (розширення файлу)
<a href="https://github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/servlets/NewsServlet.java">**NewsServlet.java**</a>



# HomeWork #13 08.03
Розширити таблицю News, додати посилання на автора (користувача) який її опублікував. Реалізувати передачу ID авторизованого користувача до бекенду, пересвідчитись у тому, що ці дані потрапляють до БД.



# HomeWork #14 11.03
На сторінці з новиною (детальний перегляд) додати блок з переліком трьох останніх новин. Клік по них також переводить до їх детального перегляду. Переконатись, що поточна новина, яка переглядається на сторінці, не входить до блоку переліку (три новини окрім даної).
<a href="https://github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/webapp/WEB-INF/news.jsp">**news.jsp**</a>



# HomeWork #15 13.03
Д.З. Створити метод UserDao::getUserById
- Перевірити його працездатність шляхом переходу на сторінки профілів різних користувачів (як автентифікованого, так і ні)
- Узгодження з попереднім ДЗ - при виводі автора новини додати посилання на його профіль
<a href="https://github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/dal/UserDao.java#L39">**UserDao.java#L39**</a>



# HomeWork #16 15.03
Обмежити доступ до детального перегляду новини, якщо вона видалена.
- додати параметр "withDeleted" методу NewsDao::getById( withDeleted )
- контролювати доступ користувача з сервлету і викликати відповідну форму NewsDao::getById
- змінити представлення детального перегляду новини: за умови, що вона видалена, відображати відмінним стилем або з повідомленням, що вона видалена
- !тільки користувачів, що мають на це право.
<a href="https://github.com/AntonDegt/JavaWeb/blob/a1b1b5d853cf79ba304bb2d74241f89efad1b8d3/src/main/java/step/learning/dal/NewsDao.java#L86">**NewsDao.java#L86**</a>



# HomeWork #17 18.03
Реалізувати валідацію даних, що надходять для зміни (UPDATE)
- у метод PUT. Використати аналогічні вимоги, як при додаванні новини, але мати на увазі, що не всі поля повинні бути при оновленні (перевіряємо тільки ті, що приходять. Обов'язковий тільки id)
- Але хоча б одне поле (окрім id) має бути
<a href="https://github.com/AntonDegt/JavaWeb/blob/cdae5d89db71afde6418de3230f3551954bce7c3/src/main/java/step/learning/servlets/NewsServlet.java#L119">**NewsServlet.java#L119**</a>



# HomeWork #18 20.03
у випадку якщо користувач має право на видалення додати кнопку "видалення".
для кожного з коментарів. Реалізувати JS функціональність для збирання даних щодо коментаря, який видаляється. На даному етапі достатньо вивести у консоль.
<a href="https://github.com/AntonDegt/JavaWeb/blob/cdae5d89db71afde6418de3230f3551954bce7c3/src/main/java/step/learning/servlets/NewsServlet.java#L46">**NewsServlet.java#L46**</a>



# HomeWork #19 22.03
Прикласти посилання на репозиторій або архів підсумкового проєкту
(не забувати про скріншоти роботи проєкту)
<a href="https://github.com/AntonDegt/JavaWeb">**JavaWeb**</a>
