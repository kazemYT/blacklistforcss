# An easy guide to remove P2W and trash servers. / Простой гайд/руководство убрать P2W и просто мусорные сервера.

# Guide on Russian. Гайд на русском.

## Первый способ

Откройте Монитор серверов в CS:S.
Перейдите на вкладку «Серверы», затем нажмите «Метки».
В разделе «Не включают» введите список тегов через запятую:

naykon,fox,bd33,serverigrcssource,no-steam,PAVLIK,MyArena.ru,nonsteam,с400

Нажмите «ОК» и «Применить фильтры».

Результат: P2W сервера пропали, и теперь остались только нормальные.

## Второй способ (тоже поможет, но часто устаревает)

Скачайте файл server_blacklist.txt с страницы.
Откройте папку с Counter-Strike: Source. (обычно C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Source\cstrike)
Зайдите в папку cfg, и скачанный server_blacklist.txt перекиньте в cfg. Всё.

Результат: какая-то часть серверов удалена, но их всё равно много.

# Guide on English. Гайд на английском

## First Method

Open the Server Monitor in CS:S.
Go to the “Servers” tab, then click “Tags.”
In the “Do not include” section, enter a list of tags:

naykon,fox,bd33,serverigrcssource,no-steam,PAVLIK,MyArena.ru,nonsteam,c400

Click “OK” and “Apply Filters.”

Result: P2W servers are gone, and now only normal ones remain.

## Second method (also helps, but often becomes outdated)

Download the server_blacklist.txt file from the page.
Open the Counter-Strike: Source folder. (usually C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Source\cstrike)
Go to the cfg folder and move the downloaded server_blacklist.txt file to cfg. That's it.

Result: some of the P2W servers are removed, but there are still many of them.

## Bonus: fun drivable car cfg for CS:S

Added file: `cfg/css_fun_car.cfg`.

What it does:
- Spawns a drivable buggy (`prop_vehicle_driveable`)
- Includes engine sound, dynamic light and sparks
- Adds quick binds (F6-F10)
- Has `script` command demo (for builds with VScript support)
- Uses short chained aliases (safe for ~255 char command limit)

How to run:
1. Copy `css_fun_car.cfg` to `.../cstrike/cfg/`
2. Start map with cheats: `sv_cheats 1`
3. Execute: `exec css_fun_car`
4. Spawn car: `car_spawn`
5. Press `E` on buggy to drive
