TXT
	https://github.com/npopova02/TXT
	
 1. Создать внешний репозиторий c названием TXT.
	зайти в GitHub и создать новый репозиторий-  Repositories-> New->TXT(name)-Public-Add a README file->Create repository
	
 2. Клонировать репозиторий TXT на локальный компьютер.
	$ git clone https://github.com/npopova02/TXT.git
	
 3. Внутри локального TXT создать файл “new.txt”.
	cd new.xml
	$ touch new.txt
	
 4. Добавить файл под гит.
	$ git status
	$ git add new.xml
	
 5. Закоммитить файл.
	$ git commit -m "Create new file"
 
 6. Отправить файл на внешний GitHub репозиторий.
	$ git push
	
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
	$ git vim new.txt
	Персональная информация кандидата
	ФИО:Попова Надежда Анатольевна
	Возраст: 38
	Количество домашних животных: 1
	ЗП: $500
	
	Esc- выходим из редактирования
	:wq->Enter - сохраняем изменения
	
 8. Отправить изменения на внешний репозиторий.
	$git push
 
 9. Создать файл preferences.txt
	$touch preferences.txt
	
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
    $vim preferences.txt
	
	Предпочтения кандидата
	Любимый фильм: Достучаться до небес
	Любимый сериал: нет
	Любимая еда: Борщ
	Любимое время года: лето
	Страна которую хотели бы посетить: Индия
	
	Esc- выходим из редактирования
	:wq->Enter - сохраняем изменения
          
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
	$cat > skills.txt
	
    Навыки кандидата:
    GitBash
	Мобильное тестирование (iOS, Android, гайдлайны)
	Dev Tools
	SQL
	Postman 
	Jmeter
	
	Cntr+C - сохранение
	
 12. Сделать коммит в одну строку.
	$  git add . && git commit -m "Adding preference and skills information"

 13. Отправить сразу 2 файла на внешний репозиторий.
  $ git push
  
 14. На веб интерфейсе создать файл bug_report.txt.
	зайти в репозиторий TXT-> кнопка Add file-> ввести bug_report.xml в поле для названия файла
	
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	ввести текст коммита в поле для названия коммита-> нажать кнопку Commit new file 
	
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
	открыть файл-> выбрать Edit this file(карандашик)-> добавить баг репорт в формате TXT
	
	id: 1
	summary: No login with valid username/password
	severity: Blocker
	priority: High
	status: Open
	precondition: Valid data: Username- standard_user, password-secret_sauce
	steps_to_reproduce:
		1. Go to www.saucedemo.com
		2. Enter valid Username/password combination
		3. Click [LOGIN] button   
	actual_resul: Login is not sucssesfull. Error message Epic sadface: Username and password do not match any user in this service appears
	expected_result: Login is sucssesfull. The home page of the site appears
  
 
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	ввести текст коммита в поле Commit changes-> нажать кнопку Commit changes
	
 18. Синхронизировать внешний и локальный репозиторий TXT
	$git pull