# Learning GIT

1. Инициализируем локальный репозиторий: git init

* настраиваем конфиг:

- git config --global user.name <name>  #задаем имя

- git config --global user.email <you_email>  #пишем свой email

* проверяем: git config --list

2. Создаем в директории несколько файлов: touch test.txt readme.txt

3. Добавляем новые файлы в индекс: git add .

4. Делаем первый коммит: git commit -m "my first commit"

5. Проверяем: git log  

#**После каждого изменения (изменения содержимого\удаления\удобавления) файлов
повторяем пункты 3-5**

---

#Пушим на GitHub

1. Регистрируем аккаунт на GitHub

2. Создаем репозиторий

3. Связываем локальный и удаленный репозитории: git remote add origin <URL>

4. Привязываем ветку: git push -u origin <branch>

5. При создании коммитов на локальном хосте, пушим их в удаленный репозиторий: git push

---



