# CloudPhotos-yandexstorage
## Запуск на Unix подобной системе

### 1. Склонировать репозиторий
### 2. Разрешить запуск
Команда:
chmod 777 { file_path publish}/CloudPhoto

Пример: chmod 777 /User/publish/CloudPhoto

### 3. Прописать алиас
a. cd ~
b. nano .bashrc
c. Вставить строку: alias cloudphoto='{ file_path publish}/CloudPhoto'

Пример: alias cloudphoto='/User/publish/CloudPhoto'
