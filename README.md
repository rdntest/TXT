<h1 align="center">TXT</h1>

 1. Создать внешний репозиторий c названием TXT - `Github Аккаунт в вебе` > _вкладка_ `Repositories` > _кнопка_ `New`
 2. Клонировать репозиторий TXT на локальный компьютер - `git clone https://github.com/XXXXX/TXT.git`
 3. Внутри локального JSON создать файл “new.txt”. touch new.txt - `touch new.txt`
 4. Добавить файл под гит - `git add new.txt`
 5. Закоммитить файл - `git commit -m 'add new.txt'`
 6. Отправить файл на внешний GitHub репозиторий - `git push`
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT - `vim new.txt`
```
firstname: Dmitry
lastname: Romanushkov
age: 27
number of pets: 1
future desired salary: 2000
```
 8. Отправить изменения на внешний репозиторий - `git commit -am 'update new.txt'` > `git push`
 9. Создать файл preferences.txt - `vim preferences.txt`
 10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```
favorite film: The Lord Of The Rings
favorite serial: GameOfThrones
favorite food: Pizza
favorite season: Winter
country i would like to visit: USA
```
 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT - `vim skills.txt`
```
Skills
1) Software testing theory,
2) Test-design techniques,
3) Working with test documentation,
4) Client-server architecture,
5) JSON and XML structure,
6) API testing via Postman,
7) Devtools practice,
8) Git and GitBash practice",
9) Payload testing via Jmeter,
10) Mobile testing,
11) SQL basics,
12) Python basics.
```
 12. Отправить сразу 2 файла на внешний репозиторий - `git add .` > `git commit -m 'send 2 files'` > `git push`
 13. На веб интерфейсе создать файл bug_report.txt - `Github Аккаунт в вебе` > `Add file` > `Create new file`
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 15. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
```JSON
Bug report #1. 
1) id: 1,
2) severity: minor,
3) priority: low,
4) environment:
-Windows 10 home, Chrome 112,
-iPhone XR, IOS 16.5
5) title: The text hasn't been translated to EN on the 'About us' page,
6) steps to reproduce: 
-step 1: Navigate to site.com,
-step 2: Click menu item 'About us',
-step 3: Select EN language,
7) actual result: "The text has been translated to EN,
8) expected result: The text hasn't been translated to EN,
9) attachments: https://linktothevideo.test,
10) author: "Poor tester"
```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 17. Синхронизировать внешний и локальный репозиторий TXT - `git pull` - _сгрузить все изменения с удаленного репозитория в локальный._
