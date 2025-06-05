# Дипломный практикум в Yandex.Cloud

## Вводная часть
Моя дипломная работа оформлена и опубликована на платформе для управления проектами и репозиториями GitLab ([https://gitlab.com/netology7252023/Diplom](https://gitlab.com/netology7252023)) и состоит из 3 проектов:
 * Primary (подготовительная часть)
 * Kubernetes (развертывание кслатера кubernetes и деплой приложения)
 * Image_build (Сборка образа с джобами)

## Запуск проекта

Для запуска проекта необходимо создать переменные в группе проектов Netology:

| Ключ  | Источник |
| ------------- | ------------- |
| billing  | ID биллинг аккаунта (Yandex.Cloud)|
| organization  | ID организации (Yandex.Cloud) |
| YC_OAUTH_TOKEN  | OAuth-токен (Yandex.Cloud) |
| GITLAB_API_TOKEN  | GitLab token (GitLab) |
| CI_REGISTRY_USER  | Username (GitLab) |
| CI_REGISTRY_PASSWORD  | User password (GitLab) |
| CI_REGISTRY  | Registry (GitLab) |

Все остальные переменные он создаст сам в ходе работы
