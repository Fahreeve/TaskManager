### Задание:

Реализовать на Python (используя любые либы) простой менеджер задач.

Его функции:

* Создание задачи на определенного пользователя. При создании этому пользователю [ответственному за задачу] должно уходить сообщение.
* Пользователь должен уметь закрыть задачу, отменить ее и отложить на определенное время.
* Когда приходит время отложенной задачи, нужно отправлять сообщение ответственному.
* Пользователь может добавить комментарий к задаче.
* Для пользователя выводить список своих задач в порядке приоритетности, а также добавить удобные фильтры для работы с задачами.
* Добавить возможность сменить ответственного. При смене новому ответственному уходит соответствующее сообщение.

Сообщения можно просто записывать в базу данных.

Плюсом будет реализация с использованием фрэймворка Django.


### Установка
```bash
pip3 install -r requirements.txt
python3 manage.py createsuperuser
python3 manage.py runserver 8000
```