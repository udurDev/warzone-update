# Сборка Warzone 2.0.15

- [Warzone-Start.zip](https://raw.githubusercontent.com/udurDev/warzone-update/main/download/Warzone-Start.zip) — TLauncher, официальный лаунчер, CurseForge
- [Warzone-Prism.zip](https://raw.githubusercontent.com/udurDev/warzone-update/main/download/Warzone-Prism.zip) — Prism Launcher / PollyMC
- [Состав сборки](MODS.md)

```
СБОРКА WARZONE — УСТАНОВКА
Minecraft 1.20.1, Forge 47.4.23. Памяти для игры: 6 ГБ (минимум 5).
Лучше ставить в ОТДЕЛЬНУЮ папку игры — чужие моды в папке mods сломают вход на сервер.

=== TLauncher / официальный лаунчер / CurseForge ===
1. Создайте установку Forge 1.20.1 (версия 47.4.23) с отдельной папкой игры:
   - TLauncher: выберите версию Forge 1.20.1 (47.4.23); в настройках укажите отдельную папку игры.
   - Официальный лаунчер: поставьте Forge 47.4.23 (установщик с files.minecraftforge.net),
     «Установки» -> «Новая» -> версия forge-47.4.23, «Папка игры» -> например C:\Games\Warzone.
   - CurseForge: Create Custom Profile -> 1.20.1 -> Forge 47.4.23 -> «Open Folder».
2. Распакуйте этот архив в папку игры (должно получиться mods\wzupdater-*.jar).
3. Запустите игру -> «Установить сборку». Игра закроется, откроется окно загрузки модов.
4. Когда появится «Сборка установлена» — запустите игру снова.
Обновления: при запуске мод сам предложит «Обновить сейчас», если сборка на сервере новее.

=== Prism Launcher / PollyMC ===
«Добавить экземпляр» -> слева «Импорт» -> в поле вставьте ССЫЛКУ на Warzone-Prism.zip
(https://raw.githubusercontent.com/udurDev/warzone-update/main/download/Warzone-Prism.zip)
или нажмите «Обзор» и выберите скачанный файл Warzone-Prism.zip (не распаковывать!) -> «ОК».
Сборка скачается при первом запуске и дальше обновляется сама — ничего делать не нужно.

Лишние моды в папке mods (не из сборки) сервер не пропустит — апдейтер переносит их в mods_disabled.

Не получилось? Лог установки: <папка игры>\.wzupdater\update.log — пришлите его администрации.
```
