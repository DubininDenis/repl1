# Домашнее задание к занятию "`Репликация и масштабирование. Часть 1`" - `Дубинин Денис`



### Задание 1
На лекции рассматривались режимы репликации master-slave, master-master, опишите их различия.

Ответить в свободной форме.

### Решение.

Master-Slave.

- Есть главный источник новых данных(Master), куда идет запись и изменения в данных
- Реплики(Slave) синхронизируют данные с Master ноды
- Клиенты пишут и читают с Master ноды и только читают со Slave ноды

Master-Master.

- Обе ноды плноправные источники новых данных, куда идет запись и изменения в данных
- Ноды синхронизируют свои данные с ситуативного "Мастера"
- Клиенты пишут и читают с любой ноды
- Работа в данном режиме - нежелательна, т.к. может привести к потерям данных.


---

### Задание 2
Выполните конфигурацию master-slave репликации, примером можно пользоваться из лекции.

Приложите скриншоты конфигурации, выполнения работы: состояния и режимы работы серверов.


### Решение.


![1](https://github.com/DubininDenis/repl1/blob/main/1.png)
![2](https://github.com/DubininDenis/repl1/blob/main/2.png)
![3](https://github.com/DubininDenis/repl1/blob/main/3.png)

---


## Дополнительные задания (со звездочкой*)

### Задание 3
 

### Решение.




