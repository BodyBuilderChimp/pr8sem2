### myRPC-client

Клиентское приложение `myRPC-client` позволяет отправлять команды на сервер для выполнения. Примеры использования:

1. Отправка команды с использованием потокового сокета (TCP):
```sh
# TCP-соединение
myrpc-client -h 127.0.0.1 -p 1337 -s -c "date"

# UDP-соединение
myrpc-client -h 127.0.0.1 -p 1337 -d -c "date"
```
