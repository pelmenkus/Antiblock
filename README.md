# Antiblock
no youtube, no discord, let's give it back
Выкидываем GoodbyeDPI — вышел самый шустрый ускоритель Ютуба и Дискорда. Работает БЕЗ VPN и вообще не сбоит — мы проверили. 

Собрали короткую инструкцию:

Выключите VPN, GoodbyeDPI и другие ускоряторы — они будут конфликтовать. 
Перейдите по ссылке в консоль Google — [тут](https://shell.cloud.google.com/?pli=1&show=ide%2Cterminal).
Вставляете в консоль строчку:

curl -sSL https://raw.githubusercontent.com/ImMALWARE/bash-warp-generator/main/warp_generator.sh | bash

В консоли появится ссылка, по ней лежит файт WARP.conf — его надо скачать.
Скачайте и установите прогу для туннеля — [тут](https://github.com/amnezia-vpn/amneziawg-windows-client/releases/download/1.0.0/amneziawg-amd64-1.0.0.msi). 
Запустите прогу и нажиме «Добавить туннель» — выбирайте наш файл WARP.conf
Нажмите «Подключить» — проследите, чтобы пошел трафик.

Если что-то не получается скачать, то установщик amnezia и сам файл warp в репозитории
Передаём и проверяем!