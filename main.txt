/boot 500mb ex2
efi 500mb (не обязательно)
подкачка столько же сколько и оперативы
/ сколько нужно для прог ex4
/home сколько нужно для себя(всё оставшееся) ex4

sudo add-apt-repository ppa:yannubuntu/boot-repair
sudo apt update
sudo apt install -y boot-repair && (boot-repair &)
 
Раскладка, num, переключение языков, ввод для окна:
    Устройства ввод

Среда, значки, блок:
    Arc, candy, в запуске sweet
    
Открытие двойным кликом в Поведении РС

Настроить мышь и тач в Устройствах ввода

Фикс анимации в экране

Управление питанием
В параметрах среды отключить потухание экрана

Настроить виджеты и нижнюю панель
Закреп нужных прог
В параметрах среды отключить потухание экрана

sudo apt install chromium-browser
sudo apt install flameshot
sudo apt install wine-stable
sudo apt install snapd
sudo snap install telegram-desktop

sudo apt install python3-pip
sudo pip3 install transliterate django bs4

sudo snap install pycharm-professional --classic
sudo snap install intellij-idea-ultimate --classic
sudo snap install datagrip --classic
sudo snap install rider  --classic
sudo snap install clion --classic
sudo snap install sublime-text --classic

Хром по умолчанию, телега, скрин на автозапуск
