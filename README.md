Команди git
Прапори git:

-m означає «message» (повідомлення). Прикріплює повідомлення до коміту.  
-v  
-u  
-p означає «prune» (вирізати). Після зв'язки буде видалено гілки, яких більше немає.  
-b означає «branch». Створення нової гілки  

Команди для гіта: P.s.: назви потрыбно писати без []  

// Відкрити папку проекту ( назва папки проекту testRepo )  

cd [project name]   

//  Ініціалізація гіт репозиторія  

git init   

// Задання перемінної origin, тобто об’єднання локальної папки і репозиторія на гітхаб  

git remote add origin git@github.com:[git url]    

// Відслідковувати зміни в файлі  

git add [file name]  

// Опис змін, для першого прийнято писати init що означає стартовий  

git commit -m 'init: Readme file'  

//  Надсилання змін на сервер гітхаб, в обрану гілку в даному випадку в master  

git push origin [branch name]  

// Звірка з гілкою на гітхаб  

git fetch origin [branch name]  

// Отримання змін з гіт  

git pull origin [name]  

// Переключення між гілками  

git checkout [name]  

// Створення гілки  

git branch [name]  

// Створення гілки і переключення на неї  

git checkout -b [yourbranchname]  