# Расположение инициализационного кода

Rails предлагает четыре стандартных места для размещения инициализационного кода:

* config/application.rb
* Конфигурационные файлы конкретных сред
* Инициализаторы
* Пост-инициализаторы

Запуск кода до Rails
--------------------

В тех редких случаях, когда вашему приложению необходимо запустить некоторый код до того, как сам Rails загрузится, поместите его до вызова `require 'rails/all'` в `config/application.rb`.