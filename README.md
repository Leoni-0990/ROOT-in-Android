RU
Для получения ROOT прав необходимо:

1. Компьютер
2. Программы для получения ROOT
3. Прошивки + кастомные Recovery (основные TWRP и  OrangeFox)

Программная составлябщая к каждому телефону разная!!!
Не получится просто что то скачать и слепить воедино - у каждого телефона разные аппаратные состовляющие

Общая инструкция для получения прав супер пользователя:
1. Разблокировка загрузчика
-  подключите телефон к ПК по USB
-  разблокируйте пункт "Для разработчиков" многократным нажатием на номер сборки в настройках телефона
-  перейдите и включите "Отладка по USB" и дайте разрешение на отладку           -! Убедитесь что провод цел !-
 - скачать Platform-tools -> https://dl.google.com/android/repository/platform-tools-latest-windows.zip?hl=ru
 - Скачиваем драйвер для устройства для процессоров MediaTek: MTK usb driver для
 - распакуйте и перейдите в папку с файлами
 - в папке зажмите [ SHIFT ] -> клик правой кнопкой мыши по пустому месту -> открыть в терминале...
 - при вводе команд может быть ошибка попробуйте в начале команды поставить:
 - .\
   - Пример:
   - adb devices
   - .\adb device
 - введите команду:
   - adb devices
 - Покажет подключенные девайсы
 - Далее:
   - adb reboot bootloader
 - На девайсе появится надпись FASTBOOT, вводим команду:
   - fastboot flashing unlock
 - ТУТ смотрим какое сообщение будет выведено на экран устройства скорее всего он спросить разблокировать или нет (YES/no) +/-
 - если так жмем [ Громкость + ]
 - Заргузчик разблокирован, перезагружаем девайс:
   - fastboot reboot

------------------------
EN
This repository is designed to help you manage a device with ROOT access and get ROOT access
Finding working unbroken and, moreover, unbroken links is a difficult matter.
To facilitate the search for modules/extensions/programs and how to use them
All actions performed are performed at your own risk
In case of unsuccessful firmware, you can contact frequent specialists - they can remotely restore the software part of almost any device
