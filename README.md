# Дипломный практикум в Yandex.Cloud

## Вводная часть
Моя дипломная работа оформлена и опубликована на платформе для управления проектами и репозиториями GitLab ([https://gitlab.com/netology7252023/Diplom](https://gitlab.com/netology7252023)) и состоит из 3 проектов:
 * primary (подготовительная часть)
 * kubernetes (развертывание кластера кubernetes и деплой приложения)
 * image_build (Сборка образа с джобами)

## Запуск проекта

Для запуска проекта необходимо создать переменные в группе проектов Netology:

| Ключ  | Источник | Плаформа |
| ------------- | ------------- | ------------- |
| billing  | ID биллинг аккаунта | Yandex.Cloud |
| organization  | ID организации| Yandex.Cloud |
| YC_OAUTH_TOKEN  | OAuth-токен| Yandex.Cloud |
| GITLAB_API_TOKEN  | GitLab token | GitLab |
| CI_REGISTRY_USER  | Username | GitLab |
| CI_REGISTRY_PASSWORD  | User password | GitLab |
| CI_REGISTRY  | Registry | GitLab |

Остальные переменные будут созданы автоматически

Далее необходимо собрать образ из image_build. Требуется замена имени образа на своё значение в CI файлах Pipeline
name: registry.gitlab.com/netology7252023/image_build:latest


При внесении изменений в файлы проекта primary, начнет создаваться инфраструктура.

После этого выполняется helm.

Открываем в браузере ip-адрес нашего балансировщика.
![](https://github.com/Granit16/NetologyDiplom/blob/main/img/pic1.png)
