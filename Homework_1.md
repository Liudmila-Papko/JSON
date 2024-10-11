# GIT Homework 1

Как отправить ДЗ на проверку.
 1. Создайте текстовый файл как в первом ДЗ по Terminal.
 2. Сценарий перенесите в этот файл.
 3. Напротив каждого действия - напишите команду в GitBash

## JSON
#### 4. Создать внешний репозиторий c названием JSON.
- перейти по ссылке https://github.com/Liudmila-Papko?tab=repositories
- нажать кнопку New
- ввести Repository name (JOSN)
- выбрать Public
- выбрать Add a README file
- нажать Create repository
- скопировать HTTPS
#### 5. Клонировать репозиторий JSON на локальный компьютер.
  ``` 
- git clone https://github.com/Liudmila-Papko/JSON.git
  ```
#### 6. Внутри локального JSON создать файл “new.json”. 
```
touch new.json
```
#### 7. Добавить файл под гит. 
```
git add new.json
```
#### 8. Закоммитить файл. 
```
git commit -m "add new file"
```
#### 9. Отправить файл на внешний GitHub репозиторий.
```
git push
```
#### 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```
vim new.json
INSERT (i)
{       
	"name":"Liudmila",
	"surname":"Papko",
	"age":"37",
	"pets":"0",
	"future salary":"100000"
}
ESC :wq
```
#### 11. Отправить изменения на внешний репозиторий. 
```
git commit -am "add file About me"
```
#### 12. Создать файл preferences.json
```
touch preferences.json
``` 
#### 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON. 
```
vim preferences.json
INSERT (i)
{
	"Film":"August Rush",
	"Serial":"Sherlock",
	"Food":"Pancakes",
	"Season":"Summer",
	"Country":"Great Britain"
}
ESC :wq
```
#### 14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON (touch skills.json)
```
vim preferences.json
INSERT (i)
{
	"skill1":"Teory of testing",
	"skill2":"Terminal",
	"skill3":"GitHub",
	"skill4":"DevTools",
	"skill5":"Fiddler",
	"skill6":"Postman",
	"skill7":"SQL",
	"skill8":"Charles",
	"skill9":"ADB",
	"skill10":"Android studio",
	"skill11":"JMeter",
	"skill12":"JS",
	"skill13":"Swagger",
	"skill14":"Webservises"
}
ESC :wq
```
#### 15. Отправить сразу 2 файла на внешний репозиторий.
```
git add preferences.json skills.json
git commit -m "Add Preferences and skills"
git push
```
#### 16. На веб интерфейсе создать файл bug_report.json.
- перейти по ссылке https://github.com/Liudmila-Papko/JSON
- нажать Add file
- выбрать из выпадающего списка + Сreate new file
- ввести название файла bug_report.json

#### 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
- нажать Commit changes
- изменить Commit message (необязательно) 
- добавить Extended description (необязательно)
- нажать Commit changes
 #### 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
- нажать на файл bug_report.json
- нажать на иконку редактирования
- ввести текст
```
{
  "ID":"1",
  "Date":"10.10.2024",
  "Severity":"Critical",
  "Environment":"Win 11 Chrome 129",
  "Title":"Button [Login] on the search page is automatically refresh the page",
  "Steps":"1. Navigate to Capital.com 2. Click on button [Search] and press Enter 3. Click button [Login]"
  "Expected Results":"Login form is opened",
  "Actual Results":"The page is refreshing",
  "Attachment":"Link",
  "Author":"Name",
  "Status":"Opened",
  "Bug comments":"null"
}
```
#### 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
- нажать Commit changes
- изменить Commit message (необязательно) 
- добавить Extended description (необязательно)
- нажать Commit changes
#### 20. Синхронизировать внешний и локальный репозиторий JSON
```
git pull
```
