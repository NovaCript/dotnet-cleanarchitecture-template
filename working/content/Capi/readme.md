# 🏗️ Capi Project - Clean Architecture

Микросервис построен по принципам Clean Architecture с четким разделением слоев и зависимостей

## 📋 Структура проектов


| Проект | Назначение | Зависимости |
| :--- | :--- | :--- |
| **Capi.API** | Web API, контроллеры, точка входа | Application, Infrastructure |
| **Capi.Application** | Бизнес-логика, сервисы, use cases | Domain |
| **Capi.Domain** | Доменные модели, интерфейсы, entities | - |
| **Capi.Infrastructure** | Данные, внешние сервисы, repositories | Application |