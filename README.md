# Homework-20

Инициализируем гит репозиторий - git init;

Создаем файл index.html;

Изменяем статус файла чтобы гит его трекал - git add index.html;

Делаем коммит с сообщением "initial commit" - git commit -m "initial commit";

Добавляем remote repository gitthub - git remote add origin https://github.com/Dmitriy2020-altair/Homework-20.git;

Делаем пуш в удаленный репозиторий - git push;

Создаем файл style.css и добавляем его в предыдущий коммит

1) git add . чтобы затрекать все файлы 
2) git commit --amend -m " текст коммита, кот заменит первый или переписываем первый "                                                                                                      
3) Пушим на сервер - git push -f origin указываем ветку. Принудительно затрет первый коммит, получится только один, как и надо. 

Меняем файл style.css

Откатываем изменения style.css
Oткатить изменения файла: 

1) до того как затрекали( git add . )  
git checkout --< имя файла > или git checkout -- . чтобы 
применить ко всем файлам в кот нужно откатить изменения;  

2) если затрекал ( сделал git add . ) 
git reset < имя файла > или git reset . чтобы применить ко 
всем файлам в кот нужно откатить слежку, убрать add . 
после повторяем git checkout -- < имя файла >, все как в 
пункте 1).

Делаем копию папки и из новой папки создаем новую ветку new-branch - git checkout -b new-branch;
Создаем файл main.js и делаем с ним коммит и пуш
1) git add .
2) git commit -m "main.js added"
3) git remote add origin https://github.com/Dmitriy2020-altair/Homework-20.git;
4) git push;

Переходим в первоначальную папку и спуливаем изменения из ветки new-branch в ветку master. git pull origin new-branch;
