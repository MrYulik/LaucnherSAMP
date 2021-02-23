# LaucnherSAMP
RU
Как настроить лаунчер и собрать его.
Требуеться: Visual Studio 2017 и выше с пакетом C#
Начнём.
1) Запускаем файл Launcher_Samp_Public.sln
2) Раскрываем в иерархии файл Launcher_Samp_Public
3) Раскрываем в иерархии файл MainWindow.xaml
4) Открываем файл MainWindow.xaml.cs
В начале кода есть такие строки:
public string IP = "5.254.105.203"; // IP Сервера
public int PORT = 7777; // ПОРТ Сервера
public static string GroupID = "cover_corporation"; // ID Группы
public static string SaitURL = "http://covercorp.tk"; // URL Сайта
Изменяйте их под свои!
5) Нажимайте кнопку Пуск если всё работает рядом с кнопкой Пуск есть Debug нажимаем на него и переводим в Release
Потом переходим в "Сборка" и нажимаем "Собрать решение"
6) Переходим в папки проекта и будет папка bin/Release/ и там exe и дополнительные dll файлы, они нужны для
полной работы лаунчера.
Спасибо за внимание!

EN
How to set up the launcher and build it.
Required: Visual Studio 2017 and up with C # package
Let's start.
1) Run the Launcher_Samp_Public.sln file
2) Expand the Launcher_Samp_Public file in the hierarchy
3) Expand the MainWindow.xaml file in the hierarchy
4) Open the MainWindow.xaml.cs file
At the beginning of the code, there are lines like this:
public string IP = "5.254.105.203"; // Server IP
public int PORT = 7777; // Server PORT
public static string GroupID = "cover_corporation"; // Group ID
public static string SaitURL = "http://covercorp.tk"; // Site URL
Change them to suit yours!
5) Press the Start button if everything works next to the Start button, there is Debug, click on it and translate it to Release
Then go to "Build" and click "Build Solution"
6) Go to the project folders and there will be a bin / Release / folder and there exe and additional dll files, they are needed for
full work of the launcher.
Thanks for attention!
