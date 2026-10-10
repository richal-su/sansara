# Управление ИТ-продуктами

Репозиторий содержит результаты выполнения сквозного учебного проекта по дисциплине «Управление ИТ-продуктами».

## Сведения о проекте

| Параметр | Значение |
|---|---|
| Название продукта | Sansara |
| Краткое название | Snsr |
| Команда | 403 |
| Учебная группа | 15.27Д-ИСТ04/25б |
| Семестр | 3 |
| Преподаватель | Мамонов Вадим Григорьевич |

## Проблема и решение

### Проблема

У компаний после проектов, изменений спецификации и закупок с запасом остаются пригодные материалы на складе: деньги уже потрачены, место занято, учёт ведётся в Excel, 1С или ERP отдельно от закупочных заявок других компаний. Продавец вынужден вручную готовить объявления и уточнять характеристики; покупателю проще обратиться к привычному поставщику, чем искать небольшую партию с неизвестным состоянием и сроком. Существующие каталоги и торги неликвидов не сопоставляют автоматически складской остаток одной стороны с будущей закупочной потребностью другой.

### Целевая аудитория

На старте — строительные, инженерные и электромонтажные компании в одном регионе (для пилота предлагаются Москва и Московская область при доступе команды к локальным клиентам). Приоритетные материалы: новые кабель, электрика, автоматика, трубы, фитинги, вентиляция, крепёж, инженерное оборудование; без скоропорта, химии и сложной б/у экспертизы на первом этапе.

### Продуктовое решение

B2B-платформа Sansara загружает остатки и закупочные потребности из Excel/CSV и (позже) 1С/ERP, нормализует номенклатуру, находит совпадения (matching с AI и жёсткими фильтрами), показывает экономию с учётом доставки и помогает закрыть сделку с подтверждением обеих сторон. Ценность: остаток одной компании становится закупкой другой до заказа у обычного поставщика.

## Внешние материалы

### Основной проект в Unidraw

- [Открыть основной проект в Unidraw](вставьте_ссылку) — **заполнить позже**

### Тематические доски

| Артефакт | Ссылка на доску Unidraw | Файл с пояснением |
|---|---|---|
| Карта пути клиента (CJM) | [ссылка](вставьте_ссылку) | [`docs/02_user_research/customer_journey_map.md`](docs/02_user_research/customer_journey_map.md) |
| Исследование рынка и конкурентов | [ссылка](вставьте_ссылку) | [`docs/01_product_discovery/competitor_analysis.md`](docs/01_product_discovery/competitor_analysis.md) |
| Продуктовая стратегия и roadmap | [ссылка](вставьте_ссылку) | [`docs/03_product_strategy/roadmap.md`](docs/03_product_strategy/roadmap.md) |
| Backlog и приоритизация | [ссылка](вставьте_ссылку) | [`docs/04_mvp_and_backlog/product_backlog.md`](docs/04_mvp_and_backlog/product_backlog.md) |
| Прототип MVP | [ссылка](вставьте_ссылку) | [`docs/04_mvp_and_backlog/mvp_scope.md`](docs/04_mvp_and_backlog/mvp_scope.md) |
| AI/ML-компонент и архитектура | [ссылка](вставьте_ссылку) | [`docs/06_ai_product/ai_solution_concept.md`](docs/06_ai_product/ai_solution_concept.md) |
| Метрики и аналитическая панель | [ссылка](вставьте_ссылку) | [`docs/07_analytics/kpi_dashboard.md`](docs/07_analytics/kpi_dashboard.md) |

> Ссылки Unidraw пока пустые — вставить перед сдачей (см. также `feedback/revision_log.md`).

## Состав команды

ФИО и вклад участников — **заполнить завтра** в файле:

- [`docs/00_course/team.md`](docs/00_course/team.md)

Кратко продублировать состав можно в таблице «Сведения о проекте» выше после заполнения `team.md`.

## Состав репозитория

```text
docs/          Документация и продуктовые артефакты
data/          Исходные и обработанные данные (выгрузки из docx, таблицы расчётов)
feedback/      Обратная связь и журнал доработок
mvp/           Описание MVP (исполняемый код пока отсутствует)
```

## Основные результаты

- Проблема и ценностное предложение: [`docs/01_product_discovery/product_vision.md`](docs/01_product_discovery/product_vision.md)
- Исследование пользователей: [`docs/02_user_research/customer_journey_map.md`](docs/02_user_research/customer_journey_map.md)
- Конкурентный анализ: [`docs/01_product_discovery/competitor_analysis.md`](docs/01_product_discovery/competitor_analysis.md)
- MVP и продуктовый backlog: [`docs/04_mvp_and_backlog/mvp_scope.md`](docs/04_mvp_and_backlog/mvp_scope.md)
- Приоритизация: [`docs/04_mvp_and_backlog/prioritization_rice.md`](docs/04_mvp_and_backlog/prioritization_rice.md)
- Roadmap: [`docs/03_product_strategy/roadmap.md`](docs/03_product_strategy/roadmap.md)
- Экономическое обоснование: [`docs/03_product_strategy/unit_economics.md`](docs/03_product_strategy/unit_economics.md)
- Метрики продукта: [`docs/07_analytics/product_metrics.md`](docs/07_analytics/product_metrics.md)
- AI/ML-компонент: [`docs/06_ai_product/ai_solution_concept.md`](docs/06_ai_product/ai_solution_concept.md)
- Итоговый отчёт: [`docs/08_final/final_report.md`](docs/08_final/final_report.md)

## MVP

- Описание MVP: [`mvp/README.md`](mvp/README.md)
- Обоснование состава MVP: [`docs/04_mvp_and_backlog/mvp_scope.md`](docs/04_mvp_and_backlog/mvp_scope.md)
- Backlog: [`docs/04_mvp_and_backlog/product_backlog.md`](docs/04_mvp_and_backlog/product_backlog.md)

## Источники наполнения репозитория

Тексты перенесены из материалов команды (файлы в `data/raw/`). Официальное название продукта в репозитории — **Sansara** (в исходных docx встречались рабочие имена Circula и DeadStock Match).

- `Circula Business model.docx` → `data/raw/business_model.txt`
- `Circula_technical_architecture.docx` → `data/raw/technical_architecture.txt`
- `mvp.docx` → `data/raw/mvp.txt`
- `Часть Максима.docx` → `data/raw/maxim_part.txt`
