# JSON 
 ### __1. Создать внешний репозиторий с названием JSON.__ 
 - *Открыть* [GitHub](https://github.com/new "Создание нового репозитория")  
 - *В поле __Repository name__ ввести __JSON__*.
 - *В чекбоксе __Public__ выбрать*:
    - [x] __Public__
    - [ ] Private
 -  *Выбрать __Add a README file__.*
 -  *Нажать __Create repository__*.
 ### __2. Клонировать репозиторий JSON на локальный компьютер.__ 
 - *В репозитории __JSON__ нажать на  __Code__ затем в разделе __HTPPS__ скопировать ссылку.*
 - *В __Gitbash__ написать команду и вставить ссылку (для Windows, вставить Shift+Insert)*
 - *`git clone https://github.com/Marlen7A/JSON.git`*
### __3. Внутри локального JSON создать файл "new.json".__ 
- *`touch new.json`*
- *`git status` файл __new.json__ отображается красным, изменения в файле не отслеживаются*.
### __4. Добавить файл под гит.__ 
- *`git add new.json`*
### __5. Закомитить файл.__ 
- *`git commit -m "add new.json"`*
### __6. Отправить файл на внешний GitHub репозиторий.__ 
- *`git push`*
### __7. Отредактировать содержание файла "new.json"-написать информацию о себе (ФИО,возраст, количество домашних животных, будущая желаемая зарплата). Все написать в формате JSON.__ 
- *`vim new.json`*
- *Insert*
 ```
 {	
	"full name":"Marlen Abliakimov Eskenderovich",
	"age":"34",
    "pets":{
	"dog":1,
	},
	"desiger_salary":"1000$"
 }
 ```
 - *Нажать __ESC__ ввести `:X`  __Enter__*
 ### __8. Отправить изменения на внешний репозиторий.__
- *`git commit -am`*
- *`git push`*
### __9. Создать файл preferences.json.__
- *`touch preferences.json`*
### __10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате JSON.__
- *`vim preferences.json`*
- *Insert*
 ```
 {
	"favorite_movie":"The Terminal",
	"favorite_series":"Suits",
	"favorite_food":"pasta",
	"favorite_season":"summer",
	"country I would like to visit":"Japan"
	}
```
 - *Нажать __ESC__ ввести `:X`  __Enter__*
### __11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.__
- *`cat > skills.json`*
```
{
	"skills":[
		"Software testing theory",
		"Linux_Terminal",
		"GitBash",
		"GitHub",
		"DevTools",
		"SQL",
		"Postman",
		"Jmeter",
		"Fiddler",
		"Python",
]
}
```
- *__Enter__*
- *__CTRL+D__*
### __12. Отправить сразу 2 файла на внешний репозиторий.__
- *`git add`*
- *`git commit -m "add preferences.json and skills.json"`*
- *`git push`*
### __13. На веб интерфейсе создать файл bug_report.json.__
- *В репозитории __JSON__ нажать __Add file__ и выбрать __Create new file.__*
-  *В поле __Name your file__ ввести __bug_report.json.__*
### __14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
-  *Нажать  __Commit new file.__*
### __15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.__
- *Открыть файл __bug_report.json,__ нажать на кнопку __Edid this file__ *






### __16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
-  *Нажать  __Commit changes.__*
### __17. Синхронизировать внешний и локальный репозиторий JSON.__
- *`git pull`*
