## Анонимные сообщения

Этот мини-проект позволяет пользователям создавать анонимные сообщения и делиться ими с другими. 


<img src="https://github.com/xaslx/Amessage/assets/32821819/c8542e1b-8827-4f99-9dc4-77acf7bfac3d" width="430" height="400">

#### Принцип работы
Пользователь вводит свою почту (на почту придет секретный ключ), и сообщение, затем генерируется секретный ключ который можно скопировать, 
затем другой пользователь имеющий секретный ключ может прочитать сообщение.
Сообщение автоматически удалится через 30 минут.


#### Стек технологий
- FastApi
- Redis
- Celery
- Jinja2
- Docker
- Также html, css, js

  ### [можно протестировать](https://amessage-5os3.onrender.com/message/create)
при открытии ссылки, нужно подождать так как при неактивности отключается
