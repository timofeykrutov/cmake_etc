Устанавливаем компилятор c++ с помощью [1]. 
Аналогичнор устанавливаем утилиту make для этого запускаем утилиту C:\msys64\msys2.exe и прописываем команду
```bash 
pacman -S make
```
Вывод оболочки: 
```bash 
resolving dependencies...
looking for conflicting packages...

Packages (1) make-4.4.1-1

Total Download Size:   0.49 MiB
Total Installed Size:  1.61 MiB

:: Proceed with installation? [Y/n] Y
:: Retrieving packages...
 make-4.4.1-1-x86_64             505.9 KiB   829 KiB/s 00:01 [###############################] 100%
(1/1) checking keys in keyring                               [###############################] 100%
(1/1) checking package integrity                             [###############################] 100%
(1/1) loading package files                                  [###############################] 100%
(1/1) checking for file conflicts                            [###############################] 100%
(1/1) checking available disk space                          [###############################] 100%
:: Processing package changes...
(1/1) installing make                                        [###############################] 100%
:: Running post-transaction hooks...
(1/1) Updating the info directory file...

```
После установки уилита make будет доступна по адресу C:\msys64\usr\bin\make.exe

Далее, чтобы обращаться к make по имени необходимо добавить ее в переменные среды пользователя в строку Path: 
![Текст с описанием картинки](path.png)

## Литература
1. [Первая программа на Windows. Компилятор g++](https://metanit.com/cpp/tutorial/1.2.php)
2. [Package: make](https://packages.msys2.org/package/make)
3. [Makefile для самых маленьких](https://habr.com/ru/articles/155201/)
4. [Просто о make](https://habr.com/ru/articles/211751/)
5. [GNU Make](http://rus-linux.net/nlib.php?name=/MyLDP/algol/gnu_make/gnu_make_3-79_russian_manual.html#SEC101)