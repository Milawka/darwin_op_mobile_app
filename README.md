# darwin_op_mobile_app
Этапы работы:
1) Я очень долго искала "готовое" приложение в playMarket, благодаря которому можно было бы взаимодейтсвовать с роботом Darwin-OP. 
2) Мне показалось, что я нашла нечто подобное, приступила к теситрованию приложения.  (https://play.google.com/store/apps/details?id=com.robotis.darwinmini&hl=ru)
3) a. Долго пыталась законектить робота к приложению 
   b. Читала мануал этого приложения
   с. После долгих и неудачных попыток я обнаружила, что данное приложение не совместимо с Darwin-OP. Обнаружила, что Darwin-OP и Darwin-mini, абсолютно разные модели (+ у Darwin-OP есть ещё несколько сборок)
4) Поняла, что всё-таки нужно ознакомиться с самим роботом. Поэтому на этом этапе я читала мануал для робота Darwin-OP.
5) Нашла ещё одно, как потом оказалось, не подходящее приложение https://play.google.com/store/apps/details?id=com.robotis.motion&hl=ru
6) Пришла к выводу, что нужно сделать какое-нибудь не сложное приложение на базе android.
7) Составила план.

Этапы разработки:
1) Подумать над функционалом
2) Сделать front-end
3) Почитать про ssh
4) Сделать back-end:
  a. Установить связь с роботом
  b. Добавить команды для управления робота
  c. Сделать список для мониторинга состояния роботов, имеющихся в лабе
  
   Функционал:
  1) Установка связи при помощи подключение к роботу по ssh
  2) Управление роботом с помощью команд: нажатие специальных кнопок на телефоне, вызывает определенные действия робота (жесты, голосовые сигналы, прочее поведение), благодаря заранее прописанному скрипту.
  3) Отслеживание состояние роботов на отдельном экране в приложении
    a. добавление имеющихся роботов в систему
    b. обновление информации о состоянии роботов


  
 
