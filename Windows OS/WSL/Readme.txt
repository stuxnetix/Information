//Info
WSL  - функция Windows 10+ не ниже 2004 версии для 10 , которая позволяет запускать среду Linux на Windows без необходимости отдельной виртуальнйо машины 
или двойной загрузки.
Функцию можно использовать для установки и запуска различных дистрибутивов Linux -> Debian , Ubuntu , Kali
------------------------>
Скачать можно с офф.сайта Microsoft -> https://www.microsoft.com/en-us/search/shop/apps?q=linux 
Можно создать свой дистрибутив своими средствами -> https://github.com/Microsoft/WSL-DistroLauncher 
Либо импортировать любой дистрибутив Linux для использользоваия с WSL -> https://learn.microsoft.com/ru-ru/windows/wsl/use-custom-distro

Команды для установки: 
win+r -> cmd -> powershell -> wsl --install

Прочие команды: 
wsl --list --online or wsl -l -o , просмотреть список доступных дистрибутивов
wsl --install -d distrname , установить нужный дистрибутив
Флаг -d означает , что это Ubuntu.

После установки будет предложено создать пользователя и пароль.

