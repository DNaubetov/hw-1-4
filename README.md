# Лабораторная работа 1
>Что тут есть

    screenshots - скриншоты работы программы
    src - исходники
    start-hadoop - скрипт для запуска NameNode и Yarn
    pom.xml - конфигурационный файл для сборки
    start-full-app - скрипт для магии

>Требование

      • Git
      • Java 8
      • Apache Maven 4.0.0
      • Hadoop 3.1.1
    
>Запуск проекта

Клонируем репозиторий на рабочий стол   
        
        git clone https://github.com/DNaubetov/hw-1-4
    
В папке hw-1-4 запускаем скрипт(он в свою очередь запустит hadoop программы):
    
    ./start-hadoop.sh

Далее в системе linux необходимо выполнить (для выполнения скрипта требуется наличие в системе команды curl):
    
    ./start-full-app.sh

Если Вы скопировали проект в другое место, то в скрипте нужно изменить путь до jar файла

Внутри скритпа имеется небольшие инструкций, просьба зайти и просмотреть!
