# SCP173Cage
SCP: CS plugin (RP)

Плагин добавляет возможность засунуть SCP-173 в клетку и новый предмет для этого.

**Установка:**
1) Распаковать архив;
2) Файлы с расширением `.lua` скопировать в папку `Plugins`. Не забудьте установить `init.lua` из репозитория `RP-Init`;
3) Файлы из папок `Android`, `Windows` скопировать в папки `Plugins/Android` и `Plugins/Windows` соответственно (путать файлы нельзя!);
4) Узнайте ОС сервера. В зависимости от ОС скопируйте в папку `Plugins/server` файл из папки архива `Windows` или `Linux`;
5) Файл с расширением `.png` скопируйте в папки `Plugins/Android` и `Plugins/Windows`.

Если вы всё сделали правильно, то должно выглядеть так:
```
[Plugins]
|--SCP173.lua
|--SCP173CageBox.lua
|--SCP173CageBoxSpawner.lua
|--[client]
|  |--[Android]
|  |  |--scp173_cage_box.png
|  |  |--scp173cage
|  |--[Windows]
|     |--scp173_cage_box.png
|     |--scp173cage
|--[server]
   |--scp173cage
```
(в квадратных скобках названия папок)
