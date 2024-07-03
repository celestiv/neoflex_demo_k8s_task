# 03 Kubernetes task

## Задание 1. Деплоим приложение

1. Скриншот вывода команды `kubectl get nodes`

![get nodes](./part1/img/get_nodes.png)

2. Скриншот манифестов deployment.yaml и service.yaml.

Скрины не делал, сами манифесты лежат в папке part1

3. Скриншот выставленного через сервис типа NodePort приложения из
Вашего репозитория

![nodeport app screenshot](./part1/img/nodeport_app.png)

4. Скриншот веб-интерфейса вашего приложения. На скриншоте должно быть
видно IP адрес и порт.

![web interface](./part1/img/web.png)

5. Скриншоты, показывающие добавление реплик приложения.

    - Увеличиваем количество реплик до 3 в манифесте deployment.yaml и применяем

    ![k apply](./part1/img/kubectl_apply.png)

    - Увеличиваем количество реплик до 5 при помощи `kubectl scale`

    ![kubectl scale](./part1/img/kubectl_scale.png)

    - Увеличиваем количество реплик до 7 пр и помощи `kubectl edit`

    ![kubectl edit](./part1/img/kubectl_edit.png)

## Задание 2. Пишем Helm чарт

1. Хелм-чарт. Можно прислать в виде ссылки на ваш репозиторий, или в виде архива, или в виде текстового документа с манифестами

Текст находится в папке `helm`

2. Скриншоты вывода команд Helm:

    • Список приложений Helm.

    ![helm list](./helm/img/helm_list.png)

    • Описание вашего чарта через команды Helm

    ![helm status](./helm/img/helm_status.png)

## Задание 3. Деплоим через ArgoCD

