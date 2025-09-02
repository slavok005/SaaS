---
name: 🐞 Bug Report
name: 🐞 Баг
description: Сообщить об ошибке
labels: [bug]
body:
  - type: textarea
    id: description
    attributes:
      label: Описание
      description: Опишите проблему
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Шаги для воспроизведения
      placeholder: |
        1. 
        2. 
        3. 
  - type: textarea
    id: expected
    attributes:
      label: Ожидаемое поведение
