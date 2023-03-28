# my-rice-arch-linux
my arch linux!







`sudo pacman -Syu`

| Команда |
| ------- |
| sudo pacman -Syu |


Copy code
sudo pacman -S brightnessctl
Чтобы увеличить яркость экрана на 50% с использованием brightnessctl, выполните следующую команду:

arduino
Copy code
brightnessctl set +50%
Аналогично, чтобы уменьшить яркость экрана на 50%, выполните следующую команду:

arduino
Copy code
brightnessctl set 50%-

Вы также можете проверить текущее значение яркости с помощью следующей команды:

arduino
Copy code
brightnessctl get
Кроме того, вы можете использовать значение яркости в процентах или в абсолютных единицах. Например, чтобы установить яркость в 50%, вы можете выполнить команду:

arduino
Copy code
brightnessctl set 50%
Или, чтобы установить абсолютное значение яркости в 4000, выполните следующую команду:

arduino
Copy code
brightnessctl set 4000
Обратите внимание, что для использования brightnessctl требуются права суперпользователя, так что вы должны запускать его с помощью sudo.
