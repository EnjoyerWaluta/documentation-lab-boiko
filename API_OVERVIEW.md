# API Overview

Це приклад технічної документації API для системи розкладу.

## GET /schedule

Отримати розклад для певної групи.

### Приклад запиту

GET /schedule?group=CS-21

### Приклад відповіді

```json
{
  "group": "CS-21",
  "schedule": [
    {
      "subject": "Programming",
      "teacher": "Ivan Petrenko",
      "room": "204",
      "time": "09:00"
    }
  ]
}
