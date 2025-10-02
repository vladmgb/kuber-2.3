## Домашнее задание к занятию «Настройка приложений и управление доступом в Kubernetes»


# Задание 1: Работа с ConfigMaps
Задача
Развернуть приложение (nginx + multitool), решить проблему конфигурации через ConfigMap и подключить веб-страницу.

Шаги выполнения

1. Создать Deployment с двумя контейнерами

Манифест: [deployment.yaml](https://github.com/vladmgb/kuber-2.3/blob/main/deployment.yaml)

<img width="452" height="123" alt="image" src="https://github.com/user-attachments/assets/97f15e95-e360-4d56-b2b9-6ee30585d539" />



3. Подключить веб-страницу через ConfigMap

 Манифест: [configmap-web.yaml](https://github.com/vladmgb/kuber-2.3/blob/main/configmap-web.yaml)  

<img width="422" height="135" alt="image" src="https://github.com/user-attachments/assets/aaafcecf-4661-41ca-8419-95b5492079a1" />


3.Проверить доступность

<img width="624" height="242" alt="image" src="https://github.com/user-attachments/assets/d7cdb566-c456-4348-aa43-d338f2ee160c" />

