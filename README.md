# Wayline

[English](#english) | [Русский](#русский)

---

## English

A waypoint editor for JSON files. Load a file, sort the route, fix the points, save.

### Download

1. Open the [latest release](https://github.com/torsheraa/wayline/releases/latest)
2. Download `Wayline-<version>-win64-setup.exe`
3. Run it and follow the installer

**Requirements:** Windows 64-bit.
The program installs into your user profile, so no administrator rights are needed. The installer is available in English and Russian.

### What it can do

- **Import and export JSON**, with a quick open of the latest file from your remembered folder
- **Route sorting** with several algorithms (nearest neighbour, 2-opt, 3-opt, Or-opt, ILS and others)
  - closed routes
  - bridges over long jumps, through existing points or by adding new points on the line
  - sorting by height layers, floor by floor
- **Editing:** find duplicates, rename points (including groups with identical coordinates), change colors, delete
- **Order and geometry:** reverse, move up/down, offset, scale, rotate, split long segments
- **Files:** merge files, compare two files, batch-sort every JSON in a folder
- **Top view (XZ)** with zoom and point selection
- **12 themes**, English and Russian interface, undo/redo

#### Hotkeys

| Key | Action |
|---|---|
| `Ctrl+O` | Import |
| `Ctrl+S` | Save |
| `Ctrl+Shift+S` | Export |
| `Alt+Up` / `Alt+Down` | Move points |
| `Delete` | Remove points |

Settings are stored in `wayline_settings.json` next to the program and are kept when you update.

### Updates

Wayline checks for new versions on startup (you can turn this off in the **Help** menu). When a new version is available, a ● mark appears next to **Help**. Open **Help** and choose the update item: the program downloads the installer, verifies its checksum, installs the update and starts the new version.

You can also check manually with **Help → Check for updates**.

Save your work before updating: the program restarts, and unsaved changes are lost.

### Windows warnings

Wayline is a new program and is not code-signed yet, so Windows SmartScreen or an antivirus may show a warning when you run the installer.

- On the SmartScreen window, click **More info → Run anyway**
- If an antivirus flags the file, it is most likely a false positive. You can check the file against the `.sha256` published next to it in the release. The in-app updater only downloads files from this repository

If you have problems, write to me (contacts below).

### License

Copyright (c) 2026 elis. All rights reserved.
Copying, editing and redistribution of the program or its code are prohibited without written permission of the author.

### Contacts and support

- Telegram: [@elis_uwu](https://t.me/elis_uwu)
- Discord: [elis.uwu](https://discord.com/users/1113476203316265000)
- Support the author: [FunPay](https://funpay.com/users/6174324/)

Found a bug or have an idea? Message me!

---

## Русский

Редактор путевых точек для JSON-файлов. Загрузил файл, отсортировал путь, поправил точки, сохранил.

### Скачать

1. Откройте [последний релиз](https://github.com/torsheraa/wayline/releases/latest)
2. Скачайте `Wayline-<версия>-win64-setup.exe`
3. Запустите файл и следуйте установщику

**Требования:** Windows 64-bit.
Программа ставится в профиль пользователя, права администратора не нужны. Установщик на русском и английском.

### Что умеет

- **Импорт и экспорт JSON**, быстрое открытие последнего файла из запомненной папки
- **Сортировка пути** несколькими алгоритмами (nearest neighbour, 2-opt, 3-opt, Or-opt, ILS и другие)
  - замкнутый маршрут
  - мосты на длинных прыжках: через существующие точки или новыми точками на линии
  - сортировка по слоям высоты, этаж за этажом
- **Редактирование:** поиск дубликатов, переименование точек (в том числе группами с одинаковыми координатами), смена цвета, удаление
- **Порядок и геометрия:** разворот, перемещение вверх/вниз, смещение, масштаб, поворот, разбиение длинных отрезков
- **Файлы:** объединение файлов, сравнение двух файлов, пакетная сортировка всех JSON в папке
- **Вид сверху (XZ)** с зумом и выбором точек
- **12 тем**, русский и английский интерфейс, undo/redo

#### Горячие клавиши

| Клавиши | Действие |
|---|---|
| `Ctrl+O` | Импорт |
| `Ctrl+S` | Сохранить |
| `Ctrl+Shift+S` | Экспорт |
| `Alt+Up` / `Alt+Down` | Переместить точки |
| `Delete` | Удалить точки |

Настройки лежат в `wayline_settings.json` рядом с программой и при обновлении сохраняются.

### Обновления

Wayline проверяет новые версии при запуске (это можно выключить в меню «Справка»). Если вышла новая версия, рядом с меню «Справка» появляется метка ●. Откройте «Справка» и выберите пункт обновления: программа скачает установщик, сверит контрольную сумму, установит обновление и запустит новую версию.

Проверить вручную можно через «Справка → Проверить обновления».

Перед обновлением сохраните работу: программа перезапускается, и несохранённые изменения теряются.

### Предупреждения Windows

Wayline новая программа и пока не подписана сертификатом, поэтому Windows SmartScreen или антивирус могут показать предупреждение при запуске установщика.

- В окне SmartScreen нажмите **Подробнее → Выполнить в любом случае**
- Если антивирус ругается на файл, скорее всего, это ложное срабатывание. Файл можно сверить с `.sha256`, который лежит рядом с ним в релизе, а механизм обновления в программе скачивает файлы только из этого репозитория

Если возникнут проблемы, напишите мне (контакты ниже).

### Лицензия

© 2026 elis. Все права защищены.
Копирование, редактирование и распространение программы или её кода запрещены без письменного разрешения автора.

### Контакты и поддержка

- Telegram: [@elis_uwu](https://t.me/elis_uwu)
- Discord: [elis.uwu](https://discord.com/users/1113476203316265000)
- Поддержать автора: [FunPay](https://funpay.com/users/6174324/)

Нашли ошибку или есть идея? Напишите мне!
