## Домашнее задание к занятию «Настройка приложений и управление доступом в Kubernetes»


# Задание 1: Работа с ConfigMaps
Задача
Развернуть приложение (nginx + multitool), решить проблему конфигурации через ConfigMap и подключить веб-страницу.

Шаги выполнения

1. Создать Deployment с двумя контейнерами

Манифесты: deployment.yaml

<img width="387" height="43" alt="image" src="https://github.com/user-attachments/assets/e143a7a6-4b61-4e2f-8a2d-fec376f352d8" />


3. Подключить веб-страницу через ConfigMap

 Манифесты: configmap-web.yaml  

 <img width="401" height="70" alt="image" src="https://github.com/user-attachments/assets/ae91665e-abb5-4489-beb0-75351955e1f9" />



3.Проверить доступность


Скриншот вывода curl или браузера
