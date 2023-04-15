ДЗ ДЕЛАЕМ ТУТ!

Внесли какие-то свои поправки, дополнения....
Почему-то перестали нажимать Ctrl + S после каждой правки в тексте...

# **<span style="color:brown">Git: Инструкция пользователя</span>**

Git (произносится «гит») — распределённая система управления версиями. Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. [1] https://ru.wikipedia.org/wiki/Git

<p align="center">
  <img src="images/git.png"/>
</p>

**<p style="text-align: center;">Рисунок 1: Эмблема git</p>** 

## **<span style= "color: green">Фишечки git</span>**

Рассмотрим фишечки git. 
Наиболее часто используемые команды:

* *<span style= "color:pink">git --version</span>*      -      выдаст в терминал версию git.
* *<span style= "color:pink">git init</span>*           -      запускает инициализацию git'а в текущей папке. Папка выбирается в меню *File* - *Open folder...* В выбранной папке создаётся скрытая папка .git, она необходима git'у для собственных нужд. 
* *<span style= "color:pink">git status</span>*         -      текущий статус состояния данной папки.
* *<span style= "color:pink">git add *<span style= "color:red">{file_name}</span>*</span>* -      указывает git'у, что указанный файл нужно начать отслеживать.
* *<span style= "color:pink">git commit -m *<span style= "color:red">"Тело комментария"</span>*</span>*    -   данная комнада создаёт commit, то есть сохранёнку, присваивая ей заданный пользователем комментарий.
* *<span style= "color:pink">git log</span>*            -      выдать журнал всех изменений отслеживаемых файлов.
* *<span style= "color:pink">git checkout *<span style= "color:red">{commit_name}</span>*</span>*         -   происходит переключение к коммиту (версии) с указанным именем. 
* *<span style= "color:pink">git checkout master</span>* -      возвращаемся в коммит (версию), помеченную как "главная", "текущая".

<p align="center">
  <img src="images/Linus.jpg"/>
</p>

**<p style="text-align: center;">Рисунок 2: Линус Торвальдс, создатель git</p>** 

* *<span style= "color:pink">git branch</span>* -     показывает, какие ветки существуют, и в какой ветке пользователь находится в данный момент.
* *<span style= "color:pink">git branch <span style= "color:red">{branch_name}</span></span>* -     создание новой ветки с именем branch_name.
* *<span style= "color:pink">git add -f <span style= "color:red">{images/git.png}</span></span>* -     добавление в отслеживаемые файла из конкретной папки.
* *<span style= "color:pink">git log --graph</span>* -     показывает граф существующих веток.