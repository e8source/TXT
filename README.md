# TXT
Work with GIT, gitbash

 1. Создать внешний репозиторий c названием TXT.
 2. Клонировать репозиторий TXT на локальный компьютер. 
 
        git clone git@github.com:e8source/TXT.git
 3. Внутри локального TXT создать файл “bio.txt”. 
 
        touch bio.txt
 4. Добавить файл под гит. 
        
        git add bio.txt
 5. Закоммитить файл. 
       
        git commit -m "add bio.txt"
 6. Отправить файл на внешний GitHub репозиторий. 
        
        git push
 7. Отредактировать содержание файла “bio.txt” - написать информацию о себе в формате TXT (ФИО, возраст, локация, роль). 
        
        nano bio.txt
 8. Отправить изменения на внешний репозиторий. 
 
        git add bio.txt
        git commit -m "edit bio.txt"
        git push
 9. Создать файл preferences.txt 
        
        touch preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях в формате TXT (музыка, игра, фильм, сериал). 
        
         nano preferences.txt
 11. Создать файл skills.txt добавить информацию о скиллах в формате TXT.
         
         touch skills.txt
         nano skills.txt
 12. Сделать коммит в одну строку. 
         
         git add . && git commit -m "add preferences.txt and skills.txt"
 13. Отправить сразу 2 файла на внешний репозиторий. 
         
         git push
 14. На веб интерфейсе создать файл bug_report.txt.
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. Синхронизировать внешний и локальный репозиторий TXT. 
         
         git pull
