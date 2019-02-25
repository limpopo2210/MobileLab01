# Лабораторна робота №1. Налаштування середовища програмування Android Studio або XCode. Робота з Git.

**Мета роботи**. Інсталювати Android Studio або  XCode, навчитись працювати із засобами відлагодження програм.

1. Встановити на власний комп'ютер Android Studio (Windows, Linux, Mac) або XСode (Mac)
1. Вивчити команди системи контролю версій git (див. [Basic Git commands](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html) )
1. Зареєструватися на GitHub.
1. Встановити git кліент на вибір: SourceTree, TortoiseGit, SmartGit або інший.
1. Створити новий проект для Android чи iOS або склонувати проект-приклад згідно до індивідуального завдання (див. нижче)
1. Розібратися зі структурою проекту
1. Розібратися зі структурою файлу AndroidManifest.xml
1. Запустити проект на емуляторі
1. Під’єднати мобільний телефон з ОС “Android” за допомогою USB і увімкнути відлагодження через USB (ADB)
1. Запустити проект на телефоні
1. Налаштувати запуск тестів. Створити хибний тест. Запустити і пересвідчитися, що хибний тест не пройшов
1. Знайти основну діяльність (MainActivity), перейти на неї
1. Вивчити роботу команди [ADB](https://developer.android.com/studio/command-line/adb)
1. Вивчити клас [Log](https://developer.android.com/reference/android/util/Log) для виводу відлагоджувальних повідомлень 
1. Перейти на клас MainActivity, знайти метод onCreate, додати лог Log.d(TAG, "Activity onCreate"), поставити Breakpoint на цьому методі.
1. Запустити проект в режимі відлагодження, розібратися з панеллю відлагодження
1. * Знайти, де знаходиться програма adb (під Linux/Mac команда find ~/Library/Android/ -name adb), та встановити режим виведення логів VERBOSE для MainActivity (<шлях до adb>/adb shell setprop log.tag.MainActivity VERBOSE)
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


# Більш детально

![Welcome screen](img/im1.png)
![](img/im2.png)
![](img/im3.png)
![](img/im4.png)
![](img/im5.png)
![](img/im6.png)
![](img/im7.png)
![](img/im8.png)
![](img/im9.png)
![](img/im10.png)
![](img/im11.png)
![](img/im12.png)
![](img/im13.png)
![](img/im14.png)
![](img/im15.png)
![](img/im16.png)
![](img/im17.png)
![](img/im18.png)
![](img/im19.png)
![](img/im20.png)
![](img/im21.png)
![](img/im22.png)
![](img/im23.png)
![](img/im24.png)
![](img/im25.png)
![](img/im26.png)
![](img/im27.png)
![](img/im28.png)
![](img/im29.png)
![](img/im30.png)
![](img/im31.png)
![](img/im32.png)
![](img/im33.png)
![](img/im34.png)
![](img/im35.png)
![](img/im36.png)
![](img/im37.png)
![](img/im38.png)
![](img/im39.png)
![](img/im40.png)
![](img/im41.png)
![](img/im42.png)
![](img/im43.png)
![](img/im44.png)
![](img/im45.png)
![](img/im46.png)
![](img/im47.png)

