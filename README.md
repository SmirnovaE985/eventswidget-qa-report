# QA Report — Events Widget
Исследовательское тестирование страницы:
https://dev.3s.info/eventswidget/

## Contents
- [QA Report](docs/qa-report.md)
- [Bugs](docs/bugs.md)
- [Checklist](docs/checklist.md)
- [Test Cases](docs/test-cases.md)
- [Observations](docs/observations.md)
- [Improvements](docs/improvements.md)


```md
## Структура репозитория

```text
eventswidget-qa-report/
├─ README.md
├─ docs/
│  ├─ qa-report.md        # основной QA-отчёт
│  ├─ bugs.md             # найденные дефекты
│  ├─ checklist.md        # чек-лист проверок
│  ├─ test-cases.md       # критичные тест-кейсы
│  ├─ observations.md     # наблюдения и особенности
│  └─ improvements.md     # предложения по улучшению
└─ artifacts/
   └─ screenshots/        # скриншоты, используемые в отчёте


## Scope
Проверялись:
- базовая работоспособность страницы
- генерация превью
- формирование embed-кода
- корректность параметра `theme`
- edge cases
- адаптивность
- UX/UI
- console / network

## Artifacts
- Screenshots: `artifacts/screenshots/`
- Network: `artifacts/network/`
- Console: `artifacts/console/`
- Responsive: `artifacts/responsive/`

## Summary
В рамках тестирования были проверены основные пользовательские сценарии конструктора календаря мероприятий, включая обязательную проверку цветовой темы «Красная» и корректность параметра `theme` в generated code.
