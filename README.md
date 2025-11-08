# SSH

## Установка и настройка

1. Установка openssh-server   
<img width="956" height="254" alt="image" src="https://github.com/user-attachments/assets/e5f4e687-d2db-40de-a3da-24e4323597c1" />

2. Проверяем запущено ли, запускаем самостоятельно
<img width="1685" height="710" alt="image" src="https://github.com/user-attachments/assets/52f64e8b-f7cc-4e52-9449-7aaeb0306e33" />

3. Открываем порт ssh, так как есть Брандмауэр
<img width="810" height="447" alt="image" src="https://github.com/user-attachments/assets/5c81fb74-d910-42e2-80a4-b1362d16ad1e" />

4. В настройках VirtualBox выставляем подключение: Сетевой мост

5. Узнаём ip виртуалки с помощью 
```
ip a
```
<img width="795" height="359" alt="image" src="https://github.com/user-attachments/assets/08bec8ea-8eea-4785-827c-27516f4ba0bb" />

## Подключение по логину
<img width="1059" height="602" alt="image" src="https://github.com/user-attachments/assets/452a6796-23e5-4b8d-891f-0fc0d07de0d1" />

## Копирование файлов
1. Копируем два текстовых файла на сервер  
<img width="1070" height="185" alt="image" src="https://github.com/user-attachments/assets/b7663062-7c2b-4f76-83c3-5a3a225c2bba" />

2. Проверяем что всё успешно скопировалось  
<img width="785" height="157" alt="image" src="https://github.com/user-attachments/assets/47438c6f-cd23-4332-bf4a-4fc39158bb49" />

3. Копируем файлы с сервера на локальную машину и проверяем:  
<img width="1049" height="120" alt="image" src="https://github.com/user-attachments/assets/2c61a39c-fd2a-466b-ad09-2272ee07cea4" />
<img width="373" height="87" alt="image" src="https://github.com/user-attachments/assets/1b120bfc-dae7-41ba-b921-fcd55669af2b" />

## Работа с ключами ssh
1. Генерируем ключи
<img width="724" height="164" alt="image" src="https://github.com/user-attachments/assets/fdcd8a77-eb4b-4a30-83af-99270838c99b" />

2. Закидываем публичный ключ на сервер
<img width="989" height="65" alt="image" src="https://github.com/user-attachments/assets/f18cb4ad-0e7a-494c-b738-d01379e94ee3" />

Проверка:   
<img width="822" height="69" alt="image" src="https://github.com/user-attachments/assets/3c9bd8e3-5b1a-4679-8246-757a9ad342e5" />

4. Добавляем настройку хоста в config
<img width="565" height="329" alt="image" src="https://github.com/user-attachments/assets/5b49dab5-ad48-45c2-a849-d99c92a61dd3" />

5. Можем подключаться к серверу без пароля (а также без указания пользователя, так как его мы указали в config):
<img width="739" height="344" alt="image" src="https://github.com/user-attachments/assets/4fde013d-e191-4672-a424-8d90f4c1bc33" />

