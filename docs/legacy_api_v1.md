# Legacy Core API Documentation (DEPRECATED)
Last update: 2021-05-12

## Base URL
`https://api.cliometrics.internal/v1`

## Entities

### Leader
Основная сущность.
**ID**: Integer (Auto-increment).
**Важно**: ID лидеров жестко зашиты в клиенте iOS версии 2.4. НЕ МЕНЯТЬ ID существующих лидеров.

### Endpoints

#### GET /leaders/{id}
Возвращает инфо о лидере.
Параметры:
- `id` (int): Уникальный номер лидера.

Пример:
`GET /leaders/1046` -> 200 OK