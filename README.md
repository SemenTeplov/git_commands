# Git консоль

* **pwd** - определить свое местонахождение

* **cd** - переход между директориями (~ - возврат в домашнюю директорию)

* **ls** - вывод всех файлов и папок в текущей директории (-a - вывод скрытых файлов и директорий)

* **touch name_file** - создание нового файла

* **mkdir name_direct** - создание директории (-p структура директории)

* **cp what_copy where_copy**  - копирование

* **mv what_move where_move**  - перемещение

* **cat name_file** - прочитать файл

* **rm name_file** - удаление файла

* **rmdir name_dir** - удаление директории

* **rm -r name_dir** - удаление директории со всеми его файлами
--


* **git config --global user.name "User Namovich"**  - установка имени в git

* **git config --global user.email username@yandex.ru** - установка имейл в git
--


* **git init** - инициализация папки как локальный git репозиторий

* **rm -rf .git** - разынициализировать  локальный git репозиторий (удаляет служебную папку .git)

* **git status** - посмотреть статус локального репозитория

* **git add name_file.txt** - отслеживание файла

* **git add --all** - отслеживание всех файлов

* **git add** . - отслеживание всей текущей папки

* **git commit -m 'Мой первый коммит!'**  - создание коммита

* **git log** - просмотр истории
--


* **ls -la .ssh/** - проверка наличия SSH ключей в домашней директории

* **ssh-keygen -t ed25519 -C "почта на GitHub"** - генерация ключа

* **ssh-keygen -t rsa -b 4096 -C "почта на GitHub"** - другой способ генерации ключ

* **ls -a ~/.ssh** - проверка сгенерированного ключа

* **clip < ~/.ssh/id_rsa.pub** - копирование ключа в буфер обмена

* **clip < ~/.ssh/id_ed25519.pub**  - второй вариант копирования ключа в буфер обмена

* **git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git**  - привязка локального репозитория с удаленным

* **git remote -v** - проверка связности репозитория

* **git push -u origin main** - связывание веток

* **git clone https://github.com/yandex-praktikum/git-clone-lesson** - клонирование репозитория
