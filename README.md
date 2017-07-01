# PurpleAbout

## [Purple](https://github.com/Kotevode/Purple)

Состав:

+ purple – собственно библиотека для организации распределенных вычилений
+ monitoring – реализация обработчиков событий, определенных в purple
+ dirichlet – все, что относится к решению задачи Дирихле
  - task_generator – программа для генерации задач. Использование:
  ```
    ./dirichlet_task_generator <размер_сетки> <количество_задач> > task
  ```
  - solver - программа расчета. Использование:
  ```
    ./dirichlet_solver -f input -o output
  ```
  
## [PurpleMonitoringServer](https://github.com/Kotevode/PurpleMonitoringServer)

Представляет собой веб-сервер для мониторинга. 
Сборка:
```
vapor build
```
Запуск:
```
vapor run
```
Подробнее в тексте ВКР и [здесь](https://docs.vapor.codes)

## [PurpleMonitoringClient](https://github.com/Kotevode/PurpleMonitoringClient)

Представлет собой клиентское приложение для отображения состояния процесса выполнения задач. Собирается под Windows 10.

По всем вопросам:

* email: kotevode@icloud.com
* Telegram: @kotevode
