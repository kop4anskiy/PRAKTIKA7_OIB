**8 ПРАКТИКА БИ ЛАЙК**

*Качаем Cellular Network Signal, узнаём данные о подключении к вышке**

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/1.jpg)

*Затем эти данные вносим на сайте и нам выходит это, всё подошло*

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/2.png)

Затем мы переходим в линукс, сканиурем сеть при помощи команды

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/3.png)

Далее меняем мак адрес 

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/4.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/5.png)

**ИДЕНТИФИКАЦИЯ НА СЕТЕВОМ И ТРАНСПОРТНОМ УРОВНЕ** 

*Сравниваем IP на онлайн сервисе и в консоли линукса*

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/6.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/7.png)

*Далее подключаем прокси и проверяем, что программа является динамически собранной *

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/8.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/9.png)

Меняем файлик proxychains4.conf и вводим нужные нам значения

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/10.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/11.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/12.png)

*после проделанных махинаций у меня не получилось получить данные о прокси соединении, однако у меня получилось открыть файрвокс с прокси-сервером*

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/13.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/14.png)

**ТОР**

Теперь перейдем к тору, после установки и модифицировании файла, добавим ключ gpg,
используемый для подписи пакетов

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/15.png)

экспортируем ключик и обновляем систему ТОРа

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/16.png)

Проверим запуск и соединение с tor сетью

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/17.png)
 
произведем запуск тестового web сервера:

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/18.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/19.png)

теперь мы ищем тор, где тор, а вот где:

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/20.png)

Находим конфигурационный файл, расскомментируем и изменим нужные строки

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/21.png)

перезапустим тор и перейдем по публичному ключу

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/22.png)

**SSH – сервер**

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/23.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/24.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/25.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/26.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/27.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/28.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/29.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/30.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/31.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/32.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/33.png)

![](https://raw.githubusercontent.com/kop4anskiy/PRAKTIKA7_OIB/main/34.png)


















