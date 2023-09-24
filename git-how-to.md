ssh-keygen -t ed25519 -C "lokhmatov.ai@phystech.edu" - создание ключа

Добавляем ключи в агента SSH
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/<name>

ssh-add .ssh/<name> - добавление ключа

ssh-add -l - просмотр ключа

git clone git@github.com:5teorema5/lokhmatov.git - клонируем репозиторий

git status - проверяем статус изменений

git add <name> - подготовка лоя коммита файла <name>
git add . - для всех папок

git commit -m “<comment>” - коммитим с комментарием <comment>

git push - отправляем изменения на сервер