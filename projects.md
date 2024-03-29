# Проекты как форма зачёта  
Существует вариативный способ получения зачёта через реализацию проекта.  
Нужно обратить внимание:  
* Если выбирается проект, то зачёт по вопросам более недоступен  
* Проект подлежит защите с презентацией и докладом  
* Вопросы будут только по реализации проекта  


## Clickhouse  
Clickhouse является OLAP системой, в рамках курса не затрагивался по практике.  
Необходимо реализовать шардирование и репликацию кластера.  
* 2 шарда
* 2 реплики на шард  
* 4 узла в кластере  

В результате должно быть развёрнуто решение, где будет кластер с двумя шардами по две реплики в каждом шарде.  

***

На защите необходимо рассказать про этапы реализации решения, сложности в процессе выполнения работы, сам принцип работы шардирования и репликации в clickhouse, применяемые технологии, список источников информации.  
Допускается публикация результатов и исходного кода в github.  
Требований к архитектуре нет.


## PostgreSQL  
Postgres является OLTP системой.  
Необходимо реализовать потоковую репликацию кластера.  
* 2 реплики на кластер  
* 3 узла в кластере  
* Допускается синхронная или асинхронная репликации к реализации

В результате должно быть развёрнуто решение, где будет кластер с 2 репликами и 1 мастер узлом.  

***

На защите необходимо рассказать про этапы реализации решения, сложности в процессе выполнения работы, сам принцип работы  репликации в PostgreSQL, применяемые технологии, список источников информации.  
Допускается публикация результатов и исходного кода в github.  
Требований к архитектуре нет.


## Mongodb  
Mongodb является OLTP системой.  
Необходимо реализовать асинхронную репликацию кластера.  
* 2 реплики на кластер  
* 3 узла в кластере  
* Допускается любое количество голосующих узлов в кластере от 3 до 7

В результате должно быть развёрнуто решение, где будет кластер с 2 репликами и 1 мастер узлом.  

***

На защите необходимо рассказать про этапы реализации решения, сложности в процессе выполнения работы, сам принцип работы  репликации в MongoDB, применяемые технологии, список источников информации.  
Допускается публикация результатов и исходного кода в github.  
Требований к архитектуре нет.
