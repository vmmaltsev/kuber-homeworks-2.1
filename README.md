# Домашнее задание к занятию «Хранение в K8s. Часть 1» - `Мальцев Виктор`

---

Задание 1
Что нужно сделать

Создать Deployment приложения, состоящего из двух контейнеров и обменивающихся данными.

    1. Создать Deployment приложения, состоящего из контейнеров busybox и multitool.
    2. Сделать так, чтобы busybox писал каждые пять секунд в некий файл в общей директории.
    3. Обеспечить возможность чтения файла контейнером multitool.
    4. Продемонстрировать, что multitool может читать файл, который периодоически обновляется.
    5. Предоставить манифесты Deployment в решении, а также скриншоты или вывод команды из п. 4.

Ответ:

манифест Deployment доступен по ссылке https://github.com/vmmaltsev/kuber-homeworks-2.1/blob/main/busybox-multitool-deployment.yaml

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_123.png)

---

Задание 2
Что нужно сделать

Создать DaemonSet приложения, которое может прочитать логи ноды.

    1. Создать DaemonSet приложения, состоящего из multitool.
    2. Обеспечить возможность чтения файла /var/log/syslog кластера MicroK8S.
    3. Продемонстрировать возможность чтения файла изнутри пода.
    4. Предоставить манифесты Deployment, а также скриншоты или вывод команды из п. 2.

Ответ:

Манифест Deployment доступен по ссылке https://github.com/vmmaltsev/kuber-homeworks-2.1/blob/main/multitool-daemonset.yaml

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_124.png)
