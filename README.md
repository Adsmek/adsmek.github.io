
## [Kozarada](https://adsmek.github.io/pages/kozarada.html)

![Kozarada · Начало концерта 16:00 ·  2019 год · Просмотры: 153](https://scontent-cph2-1.xx.fbcdn.net/v/t15.5256-10/s640x640/64483647_399395037338155_4871404967149174784_n.jpg?_nc_cat=107&_nc_sid=ad6a45&_nc_ohc=UaAza8kMSJ8AX-GeEV1&_nc_ht=scontent-cph2-1.xx&oh=9c98022d50aa81e56f3d0678dbf4ccca&oe=5F51F705)(https://adsmek.github.io/pages/kozarada.html)


## [adsmek.github.io](https://adsmek.github.io/)

 + [Go to Adsmek site readme](https://adsmek.github.io/unedtsarnd.html)
 + [Go to Adsmek.github.io](https://github.com/Adsmek/Adsmek.github.io)
 + [github.com login][https://github.com/login]

### Периодичные действия в CMD

 - В локальной папке активировать окружение Python `venv\Scripts\activate`
 - Изменить данные в страницах-файлах `*.md` папки Adsmek\`content
 - Папка со стилями `cd venv\Lib\site-packages\pelican\themes\notmyidea\static\css`
 - Папка с темами `cd venv\Lib\site-packages\pelican\themes\`
 - Обновить контент `pelican content -o Adsmek.github.io -s pelicanconf.py`


### Обновить контент:

	venv\Scripts\activate    

	pelican content
	pelican content --ignore-cache

	pelican content -o Adsmek.github.io -s pelicanconf.py
	pelican content -o Adsmek.github.io -s pelicanconf.py --ignore-cache

	pelican-themes --install venv\Lib\site-packages\pelican\themes\adsmek  --verbose


## Онлайн редакторы

 + [https://stackedit.io/app#](https://stackedit.io/app#) Редактор Markdown
 + [https://html-cleaner.com/](https://html-cleaner.com/) HTML-cleaner
 + [http://livesphinx.herokuapp.com/](http://livesphinx.herokuapp.com/) Редактор Rst
 + [vector](https://vectr.com/tmp/b1iSycHeF8/glQqtJGp6)  Svg Editor online

___

## [GitHub Pages](https://pages.github.com/)

Клонировать новый репозиторий в папку проекта:

	git clone https://github.com/username/username.github.io


## Push 

	git add --all

	git commit -m "Initial commit"

	git push -u origin master

Способ [указанный в документации](https://docs.getpelican.com/en/stable/tips.html) позволяет сохранить и отправить файлы на GitHub

	pelican content -o output -s pelicanconf.py && ghp-import output && git push origin gh-pages

___
