# moduleD1_homework


Задание:
1) Создать проект Django.
2) Добавить в него 3 статические странички, в одной из которых текст полностью будет оформлен курсивом.
3) На одной из страниц контент повторяется 2 раза без изменения content (два раза прописано {{ flatpage.content }}).
4) Одна из страниц на сайте доступна только админу (только вошедшему пользователю).
5) На одной из страниц изменены шрифты и размеры текста.
6) Сайт представляет собой оформленный Bootstrap-шаблон со встроенными пользовательскими данными.
7) Статические файлы Bootstrap загружаются через теги {% load static %} и {% static %}.

Решение:
1) проект на Django сделан;
2) Оформление курсивом на этой страничке - "templates\flatpages\italic_page.html";
3) Повторение контента на этой страничке "templates\flatpages\duble_content.html";
4) Сделано для этой странички "templates\flatpages\registered_users.html";
5) С помощью Wysiwyg-редактора изменил: размер, цвет, шрифт, текста на этой страничке "templates\flatpages\changed_text.html";
6) и 7) Сделано для страничке - "templates\flatpages\default.html";

	URL		-> 	Page
	/about/		-> ;
	/changed_text/	->	changed_text.html;
	/contacts/	->	contact_page.html;
	/duble_content/	->	duble_content.html;
	/hidden/	->	registered_users.html;
	/italic_page/	->	italic_page.html;
