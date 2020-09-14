# wg-manager

#### Установка

    ln -s $(pwd)/main /usr/local/bin/wgm

#### Создание сети:

    wgm init 10.10.10.1

#### Добавление пользователя:

    wgm add egor

###### Возвращаемый результат будет конфиг для подключения

#### Просмотр списка пользователей

    wgm list
    
#### Отключение пользователя

    wgm disable egor
    
#### Включение пользователя

    wgm enable egor
    
#### Получить конфиг для сервера

    wgm config
    
#### Получить конфиг доя клиента

    wgm client egor

#### Удалить пользователя

    wgm delete egor
    
#### Запустить wireguard конфиг

    wgm start
    
### Остановить wireguard конфиг

    wgm stop
    
#### Перезапустить wireguard конфиг

    wgm restart
    
### Синхронизировать последние изменения в wireguard

    wgm sync
    