# Battlefield 2142 - Language Changer / Смена Языка

[English](#english) | [Русский](#русский)

---

## English

### Description

This repository contains Windows Registry files that allow you to quickly change the language in Battlefield 2142. The game language can be changed between English and Russian without reinstalling the game.

### Requirements

- Windows Operating System
- Battlefield 2142 installed
- Administrator rights to modify the Windows Registry

### Files

- **Battlefield 2142 - English.reg** - Changes the game language to English
- **Battlefield 2142 - Russian.reg** - Changes the game language to Russian

### Usage Instructions

1. **Create a backup** of your registry before making any changes (recommended)
2. **Close Battlefield 2142** if it's currently running
3. **Double-click** on the desired `.reg` file:
   - For English language: `Battlefield 2142 - English.reg`
   - For Russian language: `Battlefield 2142 - Russian.reg`
4. **Confirm** the action in the Windows dialog box that appears
5. **Restart the game** to see the changes

### Important Notes

⚠️ **Warning**: These registry files modify system registry settings. Always create a backup before applying registry changes.

ℹ️ **Note**: The `InstallDir` path in the registry files is set to `D:\\Users\\Battlefield 2142`. If your game is installed in a different location, you may need to edit the `.reg` file with a text editor and change the path to match your installation directory.

ℹ️ **Compatibility**: These files are designed for 64-bit Windows systems (uses `WOW6432Node` registry path).

### How to Edit the Installation Path

If your game is installed in a different location:

1. Right-click on the `.reg` file and select "Edit" or open it with Notepad
2. Find the line: `"InstallDir"="D:\\Users\\Battlefield 2142"`
3. Change the path to your actual game installation directory
4. **Important**: Use double backslashes (`\\`) instead of single backslashes (`\`)
5. Save the file and run it as described in the Usage Instructions

### Troubleshooting

- **Game doesn't start**: Make sure the `InstallDir` path matches your actual installation location
- **Language didn't change**: Restart the game completely (close all Battlefield 2142 processes)
- **Registry error**: Ensure you have administrator rights and try running the `.reg` file as administrator

---

## Русский

### Описание

Этот репозиторий содержит файлы реестра Windows, которые позволяют быстро изменить язык в игре Battlefield 2142. Язык игры можно изменить между английским и русским без переустановки игры.

### Требования

- Операционная система Windows
- Установленная игра Battlefield 2142
- Права администратора для изменения реестра Windows

### Файлы

- **Battlefield 2142 - English.reg** - Изменяет язык игры на английский
- **Battlefield 2142 - Russian.reg** - Изменяет язык игры на русский

### Инструкция по использованию

1. **Создайте резервную копию** реестра перед внесением изменений (рекомендуется)
2. **Закройте Battlefield 2142**, если игра запущена
3. **Дважды щёлкните** по нужному файлу `.reg`:
   - Для английского языка: `Battlefield 2142 - English.reg`
   - Для русского языка: `Battlefield 2142 - Russian.reg`
4. **Подтвердите** действие в появившемся диалоговом окне Windows
5. **Перезапустите игру**, чтобы увидеть изменения

### Важные замечания

⚠️ **Предупреждение**: Эти файлы реестра изменяют системные настройки реестра. Всегда создавайте резервную копию перед применением изменений в реестре.

ℹ️ **Примечание**: Путь `InstallDir` в файлах реестра установлен как `D:\\Users\\Battlefield 2142`. Если ваша игра установлена в другом месте, вам может потребоваться отредактировать файл `.reg` в текстовом редакторе и изменить путь на соответствующий вашей установке.

ℹ️ **Совместимость**: Эти файлы предназначены для 64-битных систем Windows (использует путь реестра `WOW6432Node`).

### Как изменить путь установки

Если ваша игра установлена в другом месте:

1. Щёлкните правой кнопкой мыши по файлу `.reg` и выберите "Изменить" или откройте его в Блокноте
2. Найдите строку: `"InstallDir"="D:\\Users\\Battlefield 2142"`
3. Измените путь на актуальную директорию установки вашей игры
4. **Важно**: Используйте двойные обратные слеши (`\\`) вместо одинарных (`\`)
5. Сохраните файл и запустите его, как описано в Инструкции по использованию

### Решение проблем

- **Игра не запускается**: Убедитесь, что путь `InstallDir` соответствует фактическому расположению установки
- **Язык не изменился**: Полностью перезапустите игру (закройте все процессы Battlefield 2142)
- **Ошибка реестра**: Убедитесь, что у вас есть права администратора, и попробуйте запустить файл `.reg` от имени администратора

---

## License / Лицензия

This project is provided "as is" without any warranty. Use at your own risk.

Этот проект предоставляется "как есть" без каких-либо гарантий. Используйте на свой страх и риск.
