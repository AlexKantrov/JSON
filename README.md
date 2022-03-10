========================
### _JSON_
========================

 1. Создать внешний репозиторий c названием JSON.  
       **`Зайти на сайт github.com, создать новый репозиторий JSON, нажать Code и скопировать ссылку на репозиторий!`**
 
 2. Клонировать репозиторий JSON на локальный компьютер.  
     **`На локальном компьютере зайти в папку, где будет размещен репозиторий, запустить Gitbash и ввести команду git clone https://github.com/AlexKantrov/JSON.git`**
     
 3. Внутри локального JSON создать файл “new.json”.  
     **`cd JSON/ (Перейти в папку созданного репозитория на локальном компьютере) и ввести команду touch new.json`**
     
 4. Добавить файл под гит.  
     **`git add new.json или git add . (добавляет все существующие файлы)`**
     
 5. Закоммитить файл.  
     **`git commit -m "add new.json"`**
     
 6. Отправить файл на внешний GitHub репозиторий.  
     **`git push`**
 
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата) (Все написать в формате JSON)  
     **`vim new.json`**  
      
 ```
 {
	"Full name":"Alexey",
	"age":39,
	"Pets":{
		"quantity":1,
		"name":"Bonya" },
	"Expected salary":"1200$"
}
```
 8. Отправить изменения на внешний репозиторий.  
     **`git add new.json => git commit -m "modified new.json => git push`**
     
 9. Создать файл preferences.json  
     **`touch preferences.json`**
     
 10. В файл preferences.json добавить информацию о своих  предпочтениях (Любимый фильм, любимый сериал, любимая еда,  
 любимое время года, сторона которую хотели бы посетить) в формате JSON.  
     **`vim preferences.json`**  
  ```
  {
    "favorite movie":"fight club",
	 "favorite serial":"Breaking bad",
	 "favorite food":"meat",
	 "favorite seasons": ["spring", "summer", "autumn"],
	 "country i would like to visit": "Australia"
  }
  ```   
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON  
     **`touch skills.json => vim skills.json`**
 ```
 {
	"theory and practice": [
		"testing",
		"bag report",
		"documents",
		"method",
		"structure json",
		"oher theory about json, xml",
		"python",
		"Postman",
		"AndroidStudio"
	],
	"architecture": "client-server",
	"apps": "XCode",
	"server response": "200, 301, 303, etc"
}
``` 
 12. Отправить сразу 2 файла на внешний репозиторий.  
     **`git add . => git commit -m "new JSON file" => git push`**
     
 13. На веб интерфейсе создать файл bug_report.json  
     **`В репозитории JSON (сайт github.com) нажимаем на кнопку "add file" и нажимаем "create new file" с названием bug_report.json`**
     
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
     **`В появившемся окне нажимаем "commit new file"`**
     
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.  
     **`На вебинтерфейсе открыть файл путем редактирования и ввести текст`**
 ```
 {
"Bug Name": "Application crashes upon clicking the SAVE button while creating a new user",
"Bug ID": "(It will be automatically created by the BUG Tracking tool once you save this bug)",
"Area Path": "USERS menu -> New Users",
"Build Number": "Version Number 5.0.1",
"Severity": "HIGH (High/Medium/Low) or 1",
"Priority": "HIGH (High/Medium/Low) or 1",
"Assigned to": "Developer-X",
"Reported By": "Your Name",
"Reported On": "Date",
"Reason": "Defect",
"Status": "New/Open/Active (Depends on the Tool you are using)",
"Environment": "Windows 2003/SQL Server 2005",

"Description": "Application crashes upon clicking the SAVE button while creating a new the user, hence unable to create a new user in the application",

"Steps to Reproduce": [

"1) Login into the Application",
"2) Navigate to the Users Menu -> New User",
"3) Filled out all the user information fields",
"4) Clicked on the ‘Save’ button",
"5) Seen an error page “ORA1090 Exception: Insert values Error…”",
"6) See the attached logs for more information (Attach more logs related to the bug..IF any)",
"7) Also see the attached screenshot of the error page"],

"Expected Result": "On clicking the SAVE button, you should be prompted to a successful message New User has been created successfully",
"Actual Result": "Application crashes upon clicking the SAVE button while creating a new the user, hence unable to create a new user in the application"

}
```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
     **`Сохранить файл (нажать кнопку "commit ..")`**
     
 17. Синхронизировать внешний и локальный репозиторий JSON  
     **`git pull`**
