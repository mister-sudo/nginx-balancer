# Nginx balancer role

Ансибл роль для установки баласировщика и обратного прокси Nginx

Требования:

1 Установлен ansible (не проверялось использование других версий)

```bash
pip3 install ansible==2.10.7
```

2 Установлен pip3

```bash
sudo apt install python3-pip
```

3 Установлены зависимости для тестирования роли (при необходимости)

```bash
pip3 install -r requirements.txt --force
```

4 Пример конфигурации можно посмотреть в каталоге molecule/default/ данной роли

5 Роль для доставки ssl сертификатов <https://github.com/mister-sudo/cert-delivery.git>
