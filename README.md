# Исходники сайта [logika.info](https://logika.info)

<br/>

### Запустить logika.info для разработки

    $ docker-compose up

<br/>

### Запустить logika.info локально как сервис

<a href="https://sysadm.ru/linux/servers/containers/docker/install/">Docker</a> должен быть установлен.

    # cp logika.info.service /etc/systemd/system/logika.info.service

<br/>

    # systemctl enable logika.info.service
    # systemctl start  logika.info.service
    # systemctl status logika.info.service

http://localhost:4018
