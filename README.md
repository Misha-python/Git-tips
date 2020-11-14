# Git tips
## Основные комманды
> Примечание: \
> `repo-name` - имя репозитория, `branch-name` - название ветки

* Инициирование репозитория
  ```git
  git init
  ```
* Добавление всех файлов для коммита
  ```git
  git add --all
  ```
* Делаем коммит
  ```git
  git commit -M "ИМЯ КОММИТА"
  ```
* Создаём ветку (branch)
  ```git
  git branch branch-name
  ```
* Переходим на другую ветку (branch)
  ```git
  git checkout branch-name
  ```
* Визульный клиент git
  ```git
  gitk --all
  ```
- - - - - -
### Команды 'связи'
* Связываем локальный и глобальный репозитории (?)
  ```git
  git remote add repo-name HTTPS
  ```
* Заливаем ветку из локального репозитория но глобальный
  ```git
  git push -u repo-name branch-name
  ```
* Получаем изменения из глобального репозитория
  ```git
  git pull
  ```
  
