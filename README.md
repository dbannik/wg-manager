# wg-manager

#### Установка

    ln -s $(pwd)/main /usr/local/bin/wgm

#### Создание сети

    wgm init 10.10.10.1

#### Добавление пользователя `egor`

    wgm add egor

###### Возвращаемый результат будет конфиг для подключения

#### Просмотр списка пользователей

    wgm list
    
#### Отключение пользователя `egor`

    wgm disable egor
    
#### Включение пользователя `egor`

    wgm enable egor
    
#### Получить конфиг для сервера

    wgm config
    
#### Получить конфиг для клиента `egor`

    wgm client egor

#### Удалить пользователя `egor`

    wgm delete egor
    
#### Запустить wireguard конфиг

    wgm start
    
#### Остановить wireguard конфиг

    wgm stop
    
#### Перезапустить wireguard конфиг

    wgm restart
    
#### Синхронизировать последние изменения в wireguard

    wgm sync
    
#### Получить QR код пользователя `egor` для подключения

    wgm qr egor