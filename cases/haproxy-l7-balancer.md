# Кейс: L7-балансировщик HAProxy перед Kubernetes

## Задача

L7-балансировщик с whitelist по FQDN, сервис запретов (403 с уникальным ID и записью в БД), управление конфигом через Git.

## Решение

- HAProxy: режим HTTP, TLS-терминация, whitelist по доменам, backend к K8s по HTTPS
- Сервис запретов на отдельной VM: FastAPI, MySQL, GeoIP
- Разнесённый конфиг (head + fragments + tail), хранение в GitLab, скрипт сборки

## Инструменты

HAProxy, FastAPI, MySQL, GeoIP (mmdb), firewalld, Git

## Результат

Добавление домена = новый файл во фрагментах + `git push`; все «запрещённые» запросы логируются с ID для поддержки.
