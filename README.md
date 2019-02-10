# Лабораторна робота №1. Налаштування середовища програмування Android Studio або XCode. Робота з Git.

**Мета роботи**. Інсталювати Android Studio або  XCode, навчитись працювати із засобами відлагодження програм.

1. Встановити на власний комп'ютер Android Studio (Windows, Linux, Mac) або XСode (Mac)
1. Вивчити команди системи контролю версій git (див. [Basic Git commands](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html) )
1. Зареєструватися на GitHub.
1. Встановити git кліент на вибір: SourceTree, TortoiseGit, SmartGit або інший.
1. Створити новий проект для Android чи iOS згідно або склонувати проект-приклад згідно до індивідуального завдання (див. нижче)
1. Імпортувати проект Universal Music Player
1. Розібратися зі структурою проекту
1. Розібратися зі структурою файлу AndroidManifest.xml
1. Запустити проект на емуляторі
1. Під’єднати мобільний телефон з ОС “Android” за допомогою USB і увімкнути відлагодження через USB (ADB)
1. Запустити проект на телефоні
1. Налаштувати запуск тестів. Створити хибний тест. Запустити і пересвідчитися, що хибний тест не пройшов
1. Знайти основну діяльність (.ui.MusicPlayerActivity), перейти на неї
1. Перейти на клас BaseActivity і встановити Breakpoint на стрічці LogHelper.d(TAG, "Activity onCreate");
1. Запустити проект в режимі відлагодження, розібратися з панеллю відлагодження
1. Знайти, де знаходиться програма adb (під Linux/Mac команда find ~/Library/Android/ -name adb), та встановити режим виведення логів VERBOSE для uamp_BaseActivity (<шлях до adb>/adb shell setprop log.tag.uamp_BaseActivity VERBOSE)
1. Перейти в Android Monitor →  LogCat, Відфільтрувати журнал по рядку “Activity ”
1. Перезапустити прогаму
1. Перейти в LogCat, дослідити, у які стани переходять класи діяльностей програми (Activity) при перемиканні на інші програми
1. Написати звіт, розмістити скріншоти на DropBox (або інший ресурс) 

Скріни можна подивитися на лінком
https://www.dropbox.com/sh/fl8b09wrm99n2dl/AAAfw8xBqMotcSAfPEMFiDUaa?dl=0
Ті студенти, які мають Mac/iOS можуть виконувати подібні кроки для Xсode.


Індивідуальні завдання:
1. Basic Activity
2. Empty Activity
3. Bottom Navigation Activity
4. Fullscreen Activity
5. Master/Detail Flow
6. Navigation Drawer Activity
7. Google Maps Activity
8. Login Activity
9. Scrolling Activity
10. Tabbed Activity
