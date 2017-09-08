1 курс ИКНТ (2015-2016 гг)
=========================
   

## 1. VirtualBox ##
Для ознакомления с ОС Debian на личный ноутбук был устновлен программный продукт виртуализации для операционных систем VirtualBox. Первое знакомство с Debian GNU/Linux. Позже было принято решение установить дистрибутив Ubuntu, как вторую операционную систему на личном ноутбуке. 
+ www.virtualbox.org/
+ www.ubuntu.ru/
--------------------------  

## 2. Cистема верстки TEX и расширения LATEX ##
Основные моменты обучения взаимодействия с Latex:
+ Установка Latex на Ubuntu с использованием терминала

		sudo apt-get install texlive-full  
		sudo apt-get install texmaker  
		texmaker  
		\documentclass{article}  
		\begin{document}  
		    Hello world!  
		\end{document}  
    
+ Литература для самостоятельного чтения
+ Отчет по лабораторым за 1 семестр
+ Задание от преподавателя

Литературу, пример отчета и задание от преподавателя на паре см. в директории "Latex, SVN, GCC". 
![pic.1](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/2.jpg)

--------------------------  
## 3. Cистема контроля версий SVN ##
+ Просмотр стандартных команд

      svn help
      svn checkout  
      svn update  
      svn add  
      svn commit    
 
 + Литература: http://svnbook.red-bean.com/nightly/ru/index.html
 + Попытки использования системы контроля версий

Задание от преподавателя на паре см. в директории "Latex, SVN, GCC".
![pic.1](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/3.jpg)

--------------------------  
## 4. Сборка с использованием компилятора GCC, утилиты make, qmake ##
+ Компилятор GCC
	
	Было рекомендовано ознакомиться со следующей литературой: https://gcc.gnu.org/onlinedocs/gcc-5.2.0/gcc.pdf. Изучить оглавление, прочитать первую и вторую главу (с. 3-9) опуская абзазы про языки отличные от C/C++. Разделы 3.2, 3.3, 3.4, 3.7, 3.8 (первые три страницы), 3.9 (первую страницу), 3.10 (первые четыре страницы), 3.11 (первые три страницы), 3.13 (первую страницу) , 3.14.

+ Утилита make

	Было рекомендовано ознакомиться со следующей литературой: http://www.gnu.org/software/make/manual/make.pdf, а также изучить 	оглавление, прочитать первые пять глав.

+ Утилита qmake

	Было рекомендовано ознакомиться со следующей литературой: http://doc.qt.io/qt-5/qmake-manual.html, а также прочитать разделы 	Overview, Getting Started, Creating Project Files, Building Common Project Types, Running qmake.

+ Задание от преподавателя

Задание от преподавателя на паре см. в директории "Latex, SVN, GCC".

--------------------------  
## 5. Ubuntu ##
+ Установка с помощью установочной флешки ОС Ubuntu, как второй операционной системы
+ Основные моменты обучения взаимодействия с терминалом Ubuntu:

		sudo command // запустить команду как root
		ifconfig // показать информацию о сети 
		ping host // пропинговать host и вывести результат 
		apt-get update // обновить доступные обновления
		apt-get upgrade // обновить все пакеты
		cd /home //- перейти в директорию ‘/home’
		cd .. // перейти в директорию уровнем выше
		cd ../.. // перейти в директорию двумя уровнями выше
		cd // перейти в домашнюю директорию
		cd ~user // перейти в домашнюю директорию пользователя user  
		ls // отобразить содержимое текущей директории 
		mkdir dir1 // создать директорию с именем ‘dir1′  
		cp file1 file2 // сопировать файл file1 в файл file2
		apt-get istall application_name // установить приложение application_name
		rm бесполезно.sh  // удалить элемент
	
+ Установка и настройка git:

		sudo apt update // обновим списки пакетов из репозиториев
		sudo apt install git // загрузка и установка программы
		git clone https://github.com/git/git // клонирование репозитория
		git config --global user.name "Your Name" // идентифицируем себя, указав имя пользователя
		git config --global user.email "youremail@domain.com" // идентифицируем себя, указав адрес электронной почты пользователя 

--------------------------  
## 6. Git ##
+ Обучение: www.learngitbranching.js.org/
+ Он-лайн уроки: https://try.github.io/levels/1/challenges/1, http://pcottle.github.io/learnGitBranching/
+ Просмотр стандартных команд:

      git clone
      git add  
      git add --a 
      git rm
      git commit -m"text"   
      git push
      git merge
      git status
--------------------------  
## 7. Задания 1 семестра ##
Задания по лабораторным см. в директории "Лабораторные за 1 семестр".

Также были пояснения к следующим лабораторным:
+ К третьей лабораторной:
	stdio.h: puts, printf, scanf, fopen, fclose, fprintf, fscanf, feof, ferror (http://www.cplusplus.com/reference/cstdio/)
	stdlib.h: malloc, free (http://www.cplusplus.com/reference/cstdlib/)
	math.h (http://www.cplusplus.com/reference/cmath/)
+ К четвертой лабораторной: 
	функции для работысо строками в string.h : http://www.cplusplus.com/reference/cstring/

--------------------------
## 8. Конференция TMPA ##
Посещали конференция TMPA (http://tmpaconf.org/)
Студентам и сотрудникам политеха бесплатно, простым смертным 14 тыс руб.

--------------------------
## 9. Семинар по рефакторингу  ##
Рекомендовано было прочитать главу "Принципы рефакторинга", попытаться осознать методы рефакторинга (описаны в главах 6-12),
которые упоминаются при рассказе о конкретном запахе, а также главы 13, 14, 15.
На семинаре каждый студент группы подготовил краткое выступление (возможно с примерами) об индивидуально предложенном "запашке" кода.  Информацию брали из книги Мартина Фаулера: 
(https://www.assembla.com/spaces/octocoder/documents/djl50WGv4r5lr2dmr6bg7m/download/djl50WGv4r5lr2dmr6bg7m).

Мной был представлен "запашок" временное поле, краткого рукописного конспекта не было. 



--------------------------
## 10. Doxygen ##
На паре знакомились с функционалом. Необходимо было установить его себе, сделать документацию для 4 лабораторной работы. (http://www.stack.nl/~dimitri/doxygen/).

--------------------------
## 11. Valgrind ##
На паре знакомились с функционалом (http://www.valgrind.org/).

--------------------------  
## 12. Утилита cppcheck ##
На паре знакомились с функционалом (http://cppcheck.sourceforge.net/).
А также с командой:

	cppcheck --enable=all *

--------------------------
## 14. UML ##
Рекомендовано было прочитаь и осознать главы 1, 2, 3, 12, 16, 17, 18, 19, 32 из книги "UML. Руководство пользователя" (см. в директории UML). Также очень полезны оказались главы 5, 6, 7, 25, 29. Для построения диаграм использовался StarUML (http://staruml.io/).

--------------------------
## 15. Задание 2 семестра ##
Задание на 2 семестр 1 курса заключалось в следующем:

1. Создать репозиторий для проекта.
	
2. Создать структуру папок в репозитории как в (https://github.com/vilegzhanina/ProgrammingCourse): report, review, source, README.md, .gitignore. Синтаксис маркдаун: (https://help.github.com/categories/writing-on-github/).

3. Заполнить README.md по шаблону (https://github.com/vilegzhanina/ProgrammingCourse/blob/master/README.md).

5. Установить UML редактор (StarUML), построить в нем свои диаграммы, исходники диаграмм сохранить в папке report,
экспортированные картинки - туда же.

6. Задать архитектуру проекта: построить диаграмму компонентов, создать qt проекты под каждый компонент (библиотеку, приложение), создать интерфейс класса (только header file с классом, который будет предоставлять функции ядра системы, документировать его в нотации doxygen).

7. Доходчиво попросить коллегу из списка группы сделать ревью. Предварительно следует добавить его в collaborators,
Если Иван получив просьбу от Михаила делает ревью для Михаила, то Иван размещает в репозитории Михаила в папке review файл Arch_review, в котором перечисляет различные замечания, которые Ивану удалось придумать. Следует указывать все возможные замечания, начиная от орфографии, пунктуации и до замечаний по коду. Важно обратить внимание на диаграммы и полноту описания задания. Чем больше, тем лучше.

8. Получив результаты ревью следует либо согласится с каждым из пунктов по отдельности и внести исправления в репозиторий,
либо прокомментировать, если не согласны.

--------------------------
## 16. Система непрерывной интеграции Jenkins ##
Во время работы над заданием во втором семестре проект был подключен к системе непрерывной интеграции Jenkins (https://jenkins.io/). Благодаря системе можно было отследить падение модульных тестов во время работы программы, колечество строк кода, статистику, возвращаемую утилитами, например, cppchek или valgrind. И прочее.

--------------------------
## 17. Семинару по стандарту безопасного кодинга CERT ##
![pic.1](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/14.jpg)
![pic.2](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/15.jpg)
![pic.3](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/16.jpg)
Информацию брали отсюда:
https://www.securecoding.cert.org/confluence/pages/viewpage.action?pageId=637.

--------------------------
## 18. Эффективное использование C++ ##
![pic.1](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/17.jpg)
![pic.2](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/18.jpg)
Информацию брали отсюда:
https://www.assembla.com/spaces/octocoder/documents/dNWRdss8mr5jm5dmr6bg7m/download/dNWRdss8mr5jm5dmr6bg7m.

--------------------------
## 19. Эффективное использование STL ##
![pic.1](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/11.jpg)
![pic.2](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/12.jpg)
![pic.3](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/13.jpg)
Информацию брали отсюда:
https://www.assembla.com/spaces/octocoder/documents/dz0F9g9G8r44y3dmr6bg7m/download/dz0F9g9G8r44y3dmr6bg7m.

--------------------------
## 20. Страуструпа ##
Страуструп (на англ)
https://www.assembla.com/spaces/octocoder/documents/c-9yPMcCOr5iO0acwqjQXA/download/c-9yPMcCOr5iO0acwqjQXA
Вопросы к теор зачету	

Классы	
Глава 10
Исключения	
Глава 14
Потоки ввода-вывода	
Глава 21
Строки	
Глава 20
Обзор STL	
Глава 3
Git	

Перегрузка операторов	
Глава 11

Читайте первую и вторую главы, подумайте, какие из паттернов могли бы оказаться вам полезны.



--------------------------
## 21. Банды четырех ##
Читали первую и вторую главы, информацию брали отсюда:
https://www.assembla.com/spaces/octocoder/documents/cm3B_M3OOr46OAacwqjQWU/download/cm3B_M3OOr46OAacwqjQWU.
![pic.1](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/19.jpg)
![pic.2](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/20.jpg)
![pic.3](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/21.jpg)

--------------------------
## 22. Qt книга Шлее ##
книга Макса Шлее про Qt,
https://www.assembla.com/spaces/octocoder/documents/aotJTS9Her46C-acwqjQXA/download/aotJTS9Her46C-acwqjQXA
800+ страниц -- все как вы любите.
Большая половина из нее понадобится.

Книга про версию 4.8, но, думаю, нам достаточно.
Уже вышла книга этого же автора про 5.3,
но я сходу не нашла, где ее можно достать.
Если найдете, вы знаете что делать.

Наибольшим приоритетом для нас сейчас является выпуск mvp релиза,
который у всех нас не подразумевает gui, так что не следует бросаться в qt.

Но если вы все же не сможете удержаться, сделайте в своем репозитории ветку,
назовите ее типа gui_app, и в ней равзлекайтесь.
Если понадобятся методы из ядра, которые добавятся после ответвления,
вы всегда можете их подлить из основной ветки в gui_app.
Таким образом, не возбраняется делать gui, для функциональностей
уже реализованных методов ядра в отдельной ветке.
Но надо помнить про необходимость как-только-так-сразу выпуска mvp.

--------------------------

## 23. Семинар по стандартам С++ 11/14
![pic.1](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/22.jpg)
![pic.2](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/23.jpg)
![pic.3](https://github.com/AleksandraOrova/FirstCourse/blob/master/%D0%A1%D0%BA%D0%B0%D0%BD%D1%8B/24.jpg)
