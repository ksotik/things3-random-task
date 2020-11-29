# Скрипт для выбора случайной задачи из Things

## Установка

1. Установить библиотеку things3.things3 (https://github.com/AlexanderWillner/KanbanView#installation) одним из указанных там способов.
Например:
```
$ git clone https://github.com/AlexanderWillner/KanbanView.git
$ cd KanbanView
$ make install
```

2. Установить скрипт `random_task` из этого репозитория и скопировать его в `/usr/local/bin`:
```
$ git clone https://github.com/ksotik/things3-random-task.git
$ cp things3-random-task/random_task /usr/local/bin/
$ chmod +x /usr/local/bin/random_task
```

## Пример использования

Выбор случайной задачи из папки "Входящие":
```
$ random_task
```

Выбор случайной задачи из списка "Сегодня":
```
$ random_task t
```

Выбор случайной задачи из списка "В любое время":
```
$ random_task a
```
