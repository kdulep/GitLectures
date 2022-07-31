# Знакомство с контролем версий
* [Git](https://git-scm.com/downloads) ![Git](pictures/rsz_git-logo-2colorx2.png)
* [Github](https://github.com/) ![GitHub](pictures/rsz_github_logo.png)

Ваш сайт и новые функции, сохранение рабочей версии, папка, архив

* хранение различных версий
* возможность выбирать версию

    1. Сайт v1.0 
    2. Сайт v1.2 
    3. Сайт v2.0

# Контроль версий

* Проект 2+ человека 
* Несколько дней+

Черновики, черновики с комментариями
конфликт версий
=>много проблем неудобно долго

* google docs	люди могут изменять документы, безопасность

# Git
Линус Торвальдс создатель Linux, git

![Linus](pictures/80hxyr8x3h6z.webp)

[Reddit](https://www.reddit.com/r/linuxmasterrace/comments/6k4li1/of_young_linus_torvalds_the_finnish_way_towar)

## Пример git
* текст+текст
* текст+2 слова

>Что нужно: сохранять и перемещатся между версиями

```
git --version
	git version 2.37.1.windows.1

git init
	Initialized empty Git repository in git-education/.git/

git status
	On branch master

	No commits yet  
```
создаем файл hello wrold.md
повтор команды стрелка вверх, tab дозаполнение
```
git add hello wrold.md
git commit -m "Create new file"
[master (root-commit) e873453] Create new file
 1 file changed, 1 insertion(+)
 create mode 100644 hello wrold.md
```
```
git add hello wrold.md
git commit -m "Add new string" 
[master e560809] Add new string
 1 file changed, 2 insertions(+)

git checkout

git checkout master

git commit -m "Добавили курсив"
[master 891a604] Добавили курсив
 1 file changed, 2 insertions(+)

git add '.\hello world.md'     
git commit -m "Changed filename"
[master f833ecc] Changed filename
 1 file changed, 5 insertions(+)
 create mode 100644 hello world.md
```
***Файл должен быть записан***



# Синтаксис Markdown
[Basic Syntax](https://www.markdownguide.org/basic-syntax/)

**Жирный текст**

*Курсивный текст*

~~Зачеркнутый текст~~

### Заголовки
Уровень заголовка = -
1. Нумерованый списки
* Ненумерованый списки
    * Вложенные списки - выполняем отступы
    